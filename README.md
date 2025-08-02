# IBM_PROJECT_ON_ML

🔧 PreMaX – Predictive Maintenance for Industrial Machinery
      This project leverages machine learning to predict potential failures in industrial machines, enabling proactive maintenance and minimizing costly downtimes.

📁 Project Overview
  -  Project Title: Predictive Maintenance of Industrial Machinery
  -  Dataset: Kaggle - [Predictive Maintenance Dataset](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)
  -  Platform: IBM Cloud (Watson Machine Learning, Cloud Object Storage, Watson Studio)

📌 Problem Statement
      Industrial machines often face unexpected breakdowns such as tool wear, heat dissipation, or power failures. These issues lead to production delays and increased maintenance costs. The goal of this project is to build a machine learning model that predicts machinery failure based on sensor readings, so preventive actions can be taken early.

📌 The Challenge given: 
      Develop a predictive maintenance model for a fleet of industrial machines to anticipatefailures before they occur. This project will involve analyzing sensor data from machinery to identify patterns that precede a failure. The goal is to create a classification model that can predict the type of failure (e.g., tool wear, heat dissipation, power failure) based on real-time operational data. This will enable proactive maintenance, reducing downtime and operational costs. 

✅ Objectives
  -  Predict Failure Types: Tool Wear, Heat Dissipation, Power Failure, etc.
  -  Use sensor data to classify machine status as No Failure or Failure.
  -  Deploy the trained model using IBM Watson Machine Learning for real-time prediction.

🧠 Machine Learning Approach
              Component	                        Details
        -       Model	                    Random Forest Classifier
        -      Metrics                  	Accuracy, Precision, Recall, F1-score
        -      Data Split	                Train-Test (80-20 split)
        -    Preprocessing	              Label encoding, handling class imbalance, normalization

🚀 Deployment
The model is deployed on IBM Watson Machine Learning.

🌐 https://eu-gb.ml.cloud.ibm.com/ml/v4/deployments/premax_predictor/predictions?version=2021-05-01 
Use this endpoint to send input JSON data and get real-time failure predictions.

📌 Note: Authentication via IAM token is required to access the endpoint in production.

📂 Repository Contents
      File Name	                                              Description
  -  IBM_ML1_PROJECT.pptx	                            Complete project presentation (PPT format)
  -  SB4Academia_Problem Statements_2025.pdf	        Official problem statement document
  -  predictive_maintenance.csv	                      Dataset used for training/testing the model
  -  README.md	                                      Project overview and instructions

🔮 Future Scope
  -  Extend model to support predictive regression (time to failure).
  -  Add support for real-time streaming data using IoT sensors.
  -  Deploy with Edge Computing for local predictions at factory floors.
  -  Experiment with advanced ML techniques like XGBoost, LSTM, or AutoML.
  -  Expand solution to support multiple regions/plants.

📚 References
  -  Shivam Bansal. Predictive Maintenance Dataset
  -  IBM Watson Machine Learning Docs
  -  Random Forest Classifier - Scikit-learn Documentation
  -  Research Papers on Industrial IoT and Predictive Maintenance

