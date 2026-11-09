# AI-Based Kidney Disease Classification Using MATLAB and SVM

## Project Overview

This project presents a MATLAB-based Computer-Aided Decision Support System for classifying kidney conditions using renal ultrasound images. The system uses image processing techniques and a Support Vector Machine (SVM) algorithm to analyze ultrasound images and classify kidney conditions into different categories.

The primary objective is to assist in differentiating acute kidney failure, chronic kidney failure, and normal kidney conditions through automated image analysis.

## Objectives

- To develop an automated kidney image classification system.
- To preprocess renal ultrasound images for improved analysis.
- To extract relevant features from ultrasound images.
- To implement Support Vector Machine (SVM) for image classification.
- To provide classification results to support clinical decision-making research.

## Technologies Used

- MATLAB
- Image Processing Toolbox
- Machine Learning
- Support Vector Machine (SVM)
- Renal Ultrasound Image Dataset

## Methodology

The proposed system follows these steps:

1. **Image Acquisition:** Collect renal ultrasound images.
2. **Image Preprocessing:** Improve image quality and prepare images for analysis.
3. **Feature Extraction:** Extract relevant image features for classification.
4. **Model Training:** Train the SVM classifier using labelled image data.
5. **Image Classification:** Predict the category of an input kidney ultrasound image.
6. **Result Display:** Display the predicted classification.

## Project Structure

```text
AI-based-kidney-classification/
│
├── predict_image.m
├── svm_image_classifier.m
├── train_svm.m
└── README.md
```

## Classification Categories

The intended classification categories are:

- Normal Kidney
- Acute Kidney Failure
- Chronic Kidney Failure

## How to Run the Project

1. Install MATLAB.
2. Download or clone this repository.
3. Open the project folder in MATLAB.
4. Ensure the required image dataset is available and organized according to the code.
5. Run `train_svm.m` to train the SVM model.
6. Run the image prediction script to classify a new ultrasound image.

## Applications

- Medical image analysis
- Kidney disease classification research
- Computer-aided diagnostic support
- Biomedical image processing
- Machine learning in healthcare

## Future Enhancements

- Integration of clinical parameters such as creatinine, urea and GFR.
- Improved classification accuracy using larger and more diverse datasets.
- Development of a graphical user interface.
- Integration of additional machine learning techniques.

## Disclaimer

This project is developed for academic and research purposes. It is a prototype clinical decision-support system and is not intended to replace professional medical diagnosis.

## Author

Biomedical Engineering Project

**Domain:** Biomedical Engineering | Medical Image Processing | Machine Learning
