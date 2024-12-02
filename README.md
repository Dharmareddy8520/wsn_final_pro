
# **WSN Final Project: Privacy-Centric Intrusion Detection in Wireless Sensor Networks**

## **Project Description**
This project focuses on developing a machine learning-based Intrusion Detection System (IDS) to secure Wireless Sensor Networks (WSNs). By leveraging real-world datasets, such as **Bot-IoT** and **IDSAI**, and machine learning models, the project aims to detect both binary (e.g., attack vs. no attack) and multiclass (e.g., various attack types) intrusions.

The models evaluated include:
- Decision Tree
- Extra Trees
- Random Forest
- Gradient Boosting
- Gaussian Naive Bayes
- Linear Discriminant Analysis
- K-Nearest Neighbors
- XGBoost

## **Project Structure**
```
wsn_final/
├───Notebooks/                 # Contains Jupyter Notebooks for analysis and modeling
│   ├──   Intrusion detection using ML.ipynb        # notebook file
│_____Datasets/ 
|     |____Bot-IoT/            # Dataset 1: Bot-IoT for intrusion detection
│     └───IDSAI                 # Dataset 2: IDSAI for intrusion detection
│   ├───plots/                 # Stores plots for binary and multiclass classification
│   │   ├───binary/            # Confusion matrices for binary classification models
│   │   └───multimodel/        # Confusion matrices for multiclass classification models
├───pro/                       # Virtual environment for project dependencies (venv)
```

## **Datasets**
1. **Bot-IoT Dataset**: Focuses on IoT-related intrusions, including Distributed Denial of Service (DDoS), data theft, and other malicious behaviors.
2. **IDSAI Dataset**: Covers a wide range of real-world intrusion scenarios with detailed attack classifications.
these two files are compressed after extraction place these as your choice

## **Model Performance Metrics**

### **Binary Classification Results**
| Model                        | Accuracy | Precision | Recall   | F1-Score |
|------------------------------|----------|-----------|----------|----------|
| DecisionTree                 | 0.949990 | 0.952805  | 0.949990 | 0.949912 |
| ExtraTrees                   | 0.947220 | 0.949616  | 0.947220 | 0.947150 |
| RandomForest                 | 0.950110 | 0.952945  | 0.950110 | 0.950032 |
| GradientBoosting             | 0.950350 | 0.953287  | 0.950350 | 0.950269 |
| GaussianNB                   | 0.753595 | 0.826092  | 0.753595 | 0.739094 |
| LinearDiscriminantAnalysis   | 0.910200 | 0.919220  | 0.910200 | 0.909714 |
| KNN                          | 0.940790 | 0.941233  | 0.940790 | 0.940775 |
| XGBoost                      | 0.949650 | 0.952663  | 0.949650 | 0.949566 |

### **Multiclass Classification Results**
| Model                        | Accuracy | Precision | Recall   | F1-Score |
|------------------------------|----------|-----------|----------|----------|
| DecisionTree                 | 0.924460 | 0.921834  | 0.924460 | 0.918181 |
| ExtraTrees                   | 0.921595 | 0.917879  | 0.921595 | 0.916143 |
| RandomForest                 | 0.925230 | 0.923154  | 0.925230 | 0.918680 |
| GaussianNB                   | 0.705650 | 0.860203  | 0.705650 | 0.733621 |
| LinearDiscriminantAnalysis   | 0.759035 | 0.819685  | 0.759035 | 0.755865 |
| KNN                          | 0.914200 | 0.910238  | 0.914200 | 0.910861 |
| XGBoost                      | 0.924925 | 0.924036  | 0.924925 | 0.917440 |

## **Confusion Matrices**
### **Binary Classification Confusion Matrices**
Confusion matrix plots for binary classification models are available in the `plots/binary/` folder:
- Decision Tree
- Extra Trees
- Random Forest
- Gradient Boosting
- GaussianNB
- Linear Discriminant Analysis
- KNN
- XGBoost

### **Multiclass Classification Confusion Matrices**
Confusion matrix plots for multiclass classification models are available in the `plots/multimodel/` folder:
- Decision Tree
- Extra Trees
- Random Forest
- GaussianNB
- Linear Discriminant Analysis
- KNN
- XGBoost

## **How to Run**
1. Clone this repository:
   ```
   git clone https://github.com/Dharmareddy8520/wsn_final_pro.git
   ```
2. Navigate to the `Notebooks` directory.
3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Open Jupyter Notebook and explore the analysis and modeling notebooks.

## **Results**
The results indicate that:
- **Gradient Boosting** performed best for binary classification with an accuracy of **95.03%**.
- **Random Forest** achieved the highest performance for multiclass classification with an accuracy of **92.52%**.


## **Authors**

- Buddaraju Harshavardhan Raju 
- Arun Kumar 
- Bodige Yaso Deepika Morampudi
- Saketh Reddy Banda 
- Dharma Reddy Pandem
