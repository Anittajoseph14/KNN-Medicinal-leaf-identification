# KNN-Medicinal-leaf-identification
This repository implements a K-Nearest Neighbors (KNN) based medicinal leaf identification system using machine learning and computer vision techniques. The goal is to identify medicinal leaf based on leaf images  
# Methodology
### Image Preprocessing
1. Convert images to grayscale or RGB
2. Resize images to a fixed size (e.g., 224×224)
3. Apply histogram equalization or filtering for noise reduction
### Feature Extraction
1. Extract key features using Histogram of Oriented Gradients (HOG), Color Histograms, or Local Binary Patterns (LBP)
2. Convert features into numerical vectors
### KNN Classification
1. Train a K-Nearest Neighbors (KNN) classifier on extracted features
2. Optimize K value using cross-validation
3. Predict medicinal leaf species based on nearest neighbors
#  Dataset
The dataset consists of segmented medicinal leaf images: https://www.kaggle.com/datasets/riteshranjansaroj/segmented-medicinal-leaf-images
# Key Features
✅ Non-Deep Learning Approach: Uses traditional ML instead of CNNs  
✅ Feature-Based Classification: Extracts meaningful image features before applying KNN  
✅ Scalable & Efficient: Works well with smaller datasets and less computational power  
✅ Performance Evaluation: Uses Accuracy, Precision, Recall, and F1-score for model evaluation



