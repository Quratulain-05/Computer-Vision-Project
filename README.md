# Computer-Vision-Project
This project is a machine learning-based medical image analysis system designed to classify brain MRI scans into Benign and Malignant categories. It combines image processing, texture feature extraction, and classical machine learning to build an end-to-end diagnostic pipeline
# Features
📊 MRI image preprocessing and normalization
🧩 Tumor segmentation using thresholding + morphological operations
🔍 Texture feature extraction using GLCM (Gray-Level Co-occurrence Matrix)
📐 Geometric feature extraction (area, perimeter, circularity, centroid)
🤖 Classification using Support Vector Machine (SVM)
📈 Performance evaluation using Accuracy, Precision, Recall, and F1-score
📂 Export of feature dataset for further analysis
# Tech Stack
Python 🐍
NumPy & Pandas
Scikit-image / SciPy
Scikit-learn (SVM, metrics)
Matplotlib (visualization)
# Methodology
Load and normalize MRI slices
Segment potential tumor regions using intensity thresholding
Apply morphological operations to clean masks
Extract GLCM texture features (energy, entropy, contrast)
Extract geometric shape features
Train SVM classifier with labeled data
Evaluate performance on test set
# Results
Achieved reliable classification using handcrafted features
Balanced evaluation using train/test split
Improved performance using class-weighted SVM
⚠️ Note
This project is for educational and research purposes only and should not be used for real clinical diagnosis
