# Tissue Image Classification

## Overview  
This notebook processes a self-made tissue image dataset and performs classification by extracting features with a pre-trained MobileNet model followed by classification using a Random Forest. It includes data loading, preprocessing, visualizations, label encoding, train-test splitting, model inference, evaluation metrics, uncertainty quantification, and visualization of prediction results.

## Features  
- Load and organize tissue images into a DataFrame  
- Visualize random samples and class distributions  
- Preprocess images: resizing, normalization, and label encoding  
- Extract image features using MobileNet pretrained on ImageNet  
- Train a Random Forest classifier on extracted features  
- Evaluate model performance with accuracy, precision, recall, F1-score, classification report, and confusion matrix  
- Quantify prediction uncertainty using bootstrapping and probability distributions  
- Display correct and incorrect predictions with images

## Tech Stack  
- Python  
- Jupyter Notebook / Google Colab  
- Libraries: pandas, numpy, matplotlib, seaborn, cv2, tqdm, scikit-learn, tensorflow, PIL  

## How to Use  
1. Clone the repository.  
2. Upload the tissue image dataset zip file (`data.zip`).  
3. Run the notebook cells sequentially to preprocess data, train the model, and evaluate results.  
4. Visualize results and metrics in output cells.

## Status  
This notebook is organized and ready for clear presentation and sharing on GitHub.