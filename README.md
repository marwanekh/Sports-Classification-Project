# Sports Classification Project

This project demonstrates sports classification using a subset of 4 sports from a dataset containing 100 different sports. The dataset can be found [here on Kaggle](https://www.kaggle.com/datasets/gpiosenka/sports-classification). If you wish to use the full dataset, please download it from the provided link, it is recommended to run the project on Google Colab using GPU for faster processing.

## Description

This project leverages a pre-trained VGG16 model to extract features from sports images and uses several machine learning classifiers, including Random Forest, to classify the images. Below are the key steps and components of the project:

1. **Feature Extraction**: 
    - Using the VGG16 model pre-trained on ImageNet without the top layer.
    - Adding a `GlobalAveragePooling2D` layer to reduce the dimensions of the features.
    
2. **Classification**: 
    - Applying various classifiers such as K-Nearest Neighbors, SVM, Random Forest, Decision Tree, and Logistic Regression.
    - Main focus on Random Forest Classifier with different numbers of estimators.

3. **Evaluation**:
    - Accuracy measurement of the Random Forest Classifier.
    - Visualization of the confusion matrix.
    - Plotting accuracy vs. number of estimators.

4. **Prediction Interface**:
    - Utilizing Gradio to create a user-friendly interface for image prediction.


## Dependencies

- matplotlib
- cv2
- sklearn
- tensorflow
- gradio
- numpy
- os

### Authors
- KHALFAOUI Hassani Marwane
- [LOUKILI Taha](https://github.com/TahaLoukili)

Feel free to contribute or provide feedback to improve this project!

