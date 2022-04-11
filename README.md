**Detection of Cardiovascular Disease**

**Abstract**

We are planning to use different Machine Learning algorithms to detect cardiovascular disease in an 
individual based on the parameters like age, height, weight, gender, cholesterol, glucose, smoking, 
alcohol intake, and physical activity and compare their accuracies. 

**Motivation and Significance**

Heart disease is currently the top cause of death all over the world. Predicting cardiac disease has become 
one of the most difficult tasks in medical sector. Every minute, about one person dies from heart disease. 
According to the WHO, heart disease claims the lives of 17.9 million people each year. Although there are 
machine learning methods and methodologies for predicting heart disorders, however, suitable models 
that can predict the disease more precisely with greater accuracy and faster response time are still lacking. 
We will be using machine learning algorithm techniques to predict the individual who is suffering from 
heart disease based on several parameters (Age, height, weight, gender, cholesterol, glucose, smoking, 
alcohol intake, physical activity). Such information, if predicted in advance, can provide valuable insights 
to doctors, allowing them to adapt their diagnosis and treatment to each individual patient. This study 
will be justified by comparing the accuracy of the Support Vector Machine, Logistic Regression, and 
Random Forest algorithms for heart disease prediction, with the algorithm with the highest accuracy being 
regarded the best.

**Related Work and Background**

“Effective diagnosis of heart disease through neural networks ensembles” by Resul Das, Ibrahim Turkoglu, 
and Abdulkadir Sengur talks about diagnosis of heart disease using neural networks on Cleveland Heart 
Disease. The neural networks used in the ensemble learners were multilayer feedforward network and 
the authors used back-propagation to update the weights of the neurons. By using the proposed 
algorithms, the authors were able to obtain an accuracy of 89.01%.
“Comparing performance of logistic regression, decision trees and neural networks for classifying heart 
disease patients” by Anchana Khemphila and Veera Boonjing compares different Machine Learning 
algorithms for classification of heart disease patients. They used logistic regression, decision trees, and 
neural networks on the Cleveland Heart Disease. In decision tree algorithm, they used Classification and 
Regression Tree (CART) algorithm for making tree and used Gini index for deciding nodes. In neural 
networks, they used multilayer feedforward network and back-propagation for updating the weights. The 
authors were able to obtain an accuracy of 79.3% in Decision Trees, 80.2% in Neural Networks, and 77.7% 
Logistic Regression.

**Proposed Work and Methods**

In this project, we will be following steps as mentioned below.
• Data Pre-Processing
• Exploratory Data Analysis
• Understanding the Data (Finding Correlation)
• Feature Selection
• Machine Learning Model
• Comparing Accuracies of different ML Models

**We are planning to use 3 Machine Learning Algorithms:**

• Random Forest Classification
• Logistic Regression Classification
• Support Vector Machine Classification
In the Data Pre-Processing, we will be cleaning the missing data. We will also take care of the data out of 
range. After the Data Pre-Processing step, we will be doing Exploratory Data Analysis to understand the 
data. After this step, we will plot correlation matrix to find which attributes are correlated with the target 
variable. Based on the correlation matrix, we will decide our features for ML models. We will then split 
the data into training and validation sets. And once we train the data and find the accuracies of the 
proposed model, we will compare the accuracies of all models.
Dataset: Link
The dataset contains 11 different attributes and 1 target variable. Below is the description of the dataset 
we will be using in our project. The dataset contains around 69,000 data entries. 
1. Age | Objective Feature | age | int (days)
2. Height | Objective Feature | height | int (cm) |
3. Weight | Objective Feature | weight | float (kg) |
4. Gender | Objective Feature | gender | categorical code |
5. Systolic blood pressure | Examination Feature | ap_hi | int |
6. Diastolic blood pressure | Examination Feature | ap_lo | int |
7. Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above 
normal |
8. Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |
9. Smoking | Subjective Feature | smoke | binary |
10. Alcohol intake | Subjective Feature | alco | binary |
11. Physical activity | Subjective Feature | active | binary |
12. Presence or absence of cardiovascular disease | Target Variable | cardio | binary | 
