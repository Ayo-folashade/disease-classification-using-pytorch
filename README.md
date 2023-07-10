# Breast Cancer Classification
This project focuses on breast cancer classification using a dataset from the Breast Cancer Wisconsin (Diagnostic) Data Set. The dataset contains various features derived from breast mass images, such as radius, texture, perimeter, area, smoothness, compactness, concavity, symmetry, and more.

## Project Overview
The project includes the following steps:

- **Data Loading and Exploration:** The dataset is loaded using pandas and explored by examining the data types, summary statistics, and missing values.

- **Data Preprocessing:** The dataset is preprocessed by dropping unnecessary columns and encoding the diagnosis labels (benign or malignant) to numerical values.

- **Exploratory Data Analysis (EDA):** The distributions of different features are visualized using histograms to gain insights into the data.

- **Correlation Analysis:** The correlation between features is analyzed by creating a correlation matrix and visualizing it as a heatmap.

- **Model Training and Evaluation:** The dataset is split into training and testing sets. A disease classification model is defined using PyTorch, with a two-layer fully connected neural network. The model is trained on the training set using the Adam optimizer and cross-entropy loss. Finally, the trained model is evaluated on the test set to calculate the accuracy.

The project aims to classify breast mass images into benign or malignant cases, providing a potential tool for early breast cancer detection.

## Dependencies
The following were used for this project:
- Python
- Pandas
- NumPy
- Plotly
- Scikit-learn
- PyTorch

## Dataset
The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) Data Set. It consists of 569 instances, each with 32 features and a target variable indicating the diagnosis (benign or malignant).

Results
After training the disease classification model, it achieved a test accuracy of approximately 95.6%. This indicates the model's ability to classify breast mass images into benign or malignant cases.

## Conclusion
Breast cancer classification plays a crucial role in early detection and effective treatment. This project demonstrates the process of building a disease classification model using machine learning techniques. By analyzing various features derived from breast mass images, the model can make accurate predictions and aid in the early detection of breast cancer.

Note: This project should not be considered as a substitute for medical advice or diagnosis. It is meant for educational and research purposes only.


## License
The code and documentation in this project are licensed under the MIT License. 
