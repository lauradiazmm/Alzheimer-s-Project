<img src="https://pbs.twimg.com/profile_images/1392422291808587776/BSCkw4DW_400x400.jpg" alt="IDbootcamp Logo" width="100"/>


# Prediction Models for Alzheimer's Detection 🧠
*Laura Díaz-Muñoz Manzanares*


## Content
- [Project Description](#project-description-📝)
- [Dataset](#dataset-🗂)
- [Workflow](#workflow)
- [Technologies](#technologies)

## Project Description 📝
**Prediction Models for Alzheimer's Detection**: This project focuses on developing an effective predictive model for Alzheimer's disease, using both **machine learning (Random Forest, XGBoost)** and **deep learning (CNN)** on clinical data and neuroimages(MRI). The comprehensive approach involves preprocessing clinical and imaging data from the OASIS-3 dataset to optimize model performance.

## Dataset 🗂
The project utilizes the OASIS-3 dataset, comprising clinical, cognitive, and neuroimaging data from 1378 participants over 30 years. The dataset includes diverse subjects, from cognitively normal adults to individuals in various stages of cognitive impairment. The combination of T1w MRI sequences and clinical data makes OASIS-3 a valuable resource for Alzheimer's prediction.

Example of the dataset "health" with clinical data about the subjects. 
<img src="https://github.com/lauradiazmm/Alzheimer-s-Project/blob/main/Data/Image%20example%20dataset.png">

Example of MRI images of a subject without Alzheimer (left) and with the disease (right).
<img src="https://github.com/lauradiazmm/Alzheimer-s-Project/blob/main/Data/Image%20example%20Tw1.png">

## Workflow 📈
The workflow encompasses data preprocessing, model application, and evaluation. Notable steps include: 
* Handling missing values
* Addressing class imbalance
* Testing multiple machine learning models for optimal recall and precision
* Preprocessing T1w MRI images
* Exploring custom and pre-trained CNNs (VGG16)
* Assessing model performance

## Technologies 💻
- Programming Language: Python
- Data Manipulation and Analysis: NumPy, Pandas
- Machine Learning: Scikit-Learn, XGBoost, Random Forest
- Deep Learning: TensorFlow, Keras
- Data Visualization: Matplotlib, Seaborn
- Neural Networks: Convolutional Neural Networks (CNNs)-VGG16
- Model Evaluation: Accuracy, Recall, Precision, F1-Score, ROC Curve
- Project Documentation: Jupyter Notebooks



