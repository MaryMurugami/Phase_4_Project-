
## Image Classification with Deep Learning

This image classifiaction project with deep learning was carried out by Part-Time Moringa Students (**Team 5 - Darvin, Mary, Shadrack & Marvin**) under the supervision of Technical Mentor Samwel Jane on June 2023 as part of their end of phase deliverable.

We shall be using the CRoss-Industry Standard Process for Data Mining (CRISP-DM) Framework to organize this project.

 - Business Understanding
 - Data Understanding
 - Data Preparation
 - Modelling & Evaluation
 - Recommendations/Conclussion
## 1 Introduction

Application of Machine Learning, Deep Learning or/and Artifical Intelligence has increased tremendiously in the field of medicine over the past few years. Especially if we see sub-field of medical imagings in which we try to analyse images of Xrays, ECGs (Electrocardiogram) and other technologies to diagnose diseases or ailments in various patients.


## 1.0 Business Understanding:


Pneumonia is a leading cause of death worldwide affecting one or both lungs and early detection is crucial for effective treatment.Chest xrays are used in the detection of pneumonia which can be bacterial or viral. Radiotherapists often use
manual interpretation of chest X-ray images to diagnose pneumonia, this time consuming process is prone to human error leading to delayed diagnosis and treatment.

Ojective: Develop a deep learning model to automate the process of pneumonia detection from chest X-ray images, enabling faster and more accurate diagnosis.


## 2.0 Data Understanding:

A large dataset of labeled chest X-ray images, including both pneumonia-positive and pneumonia-negative cases was downloaded from Kaggle.com. We performed exploratory data analysis to understand data characteristics, identify any data quality issues, explored the potential features that can be used to aid pneumonia detection. The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal) - labelled data

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. We then proceeded to perform data exploration: Understand the characteristics of the data, identify any data quality issues, and explore potential patterns or features that can aid in pneumonia detection.

## 3.0 DATA PREPARATION

**Data cleaning**: Address any missing values, outliers, or inconsistencies in the dataset. Feature engineering: Extract meaningful features from the chest X-ray images that can contribute to pneumonia detection, such as texture patterns or lung region segmentation. Data transformation: Normalize or standardize the data as required for the deep learning model.

## 4.0 MODELLING & EVALUATION

**Modeling**: deep learning architecture for pneumonia detection, such as Convolutional Neural Networks (CNNs). Train the model using the prepared dataset, optimizing the model's parameters and hyperparameters. Validate and evaluate the model's performance using appropriate evaluation metrics, such as accuracy, sensitivity, specificity, or area under the receiver operating characteristic curve (AUC-ROC).

**Evaluation**: Assess the model's performance against the project objectives, considering factors like accuracy, speed, and interpretability. Identify any limitations or areas for improvement in the model's performance. Iterate on the modeling process if necessary, by refining the architecture, adjusting hyperparameters, or gathering additional data. Deployment:

Integrate the trained model into a software or web-based application that can accept chest X-ray images as input and provide automated pneumonia detection. Test the deployed system thoroughly to ensure its functionality, reliability, and accuracy. Monitor the system's performance in real-world scenarios and make necessary updates or improvements as needed. Maintenance:

Continuously monitor and evaluate the system's performance, incorporating feedback from radiologists and healthcare professionals. Update the model periodically to account for new data, evolving medical guidelines, or advancements in deep learning techniques.


## 5.0 RECOMMENDATIONS/CONCLUSSION

This model can be used in Healthcare sector in the radiological department to assist predict chest xray images easily and accutately. Similar model likewise can be improved on and deployed to assist with detection of any infectious lung diseases.

