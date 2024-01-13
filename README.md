# PredictingHospitalReadmission
- The goal of this repo is to provide a realistic setting for a machine learning application. The UCI [dataset]((https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008)) includes over 50 features representing patient and hospital outcomes. 

- The aim is to predict which patients will need hospital readmission. 

- This tutorial covers most steps in the ML pipeline. The table of contents in the notebook is as follows:

[1 Understanding the dataset](#1)
  - [1.1 Characteristics of the dataset](#1.1)
  - [1.2 Challenges of the dataset](#1.2)
  - [1.3 Data Cleaning](#1.3)
  - [1.4 Descriptive Statistics](#1.4)

[2 Data Assembling and Preprocessing](#2)

[3 Machine Learning Pipeline](#3)
  - [3.1 Models](#3.1)
  - [3.2 Metrics](#3.2)
  - [3.3 Cross Validation](#3.3)
  - [3.4 Plotting Hyperparameters against Performance](#3.4)
  - [3.5 Performance Comparison](#3.5)

[4 Alternative Pipeline](#4)
  - [4.1 Pipline including Feature Selection](#4.1)
  - [4.2 Model Evaluation with Feature Selection](#4.2)
  - [4.3 Comparion of Models Performance](#4.3)

[5 Model Interpretation](#5)
  - [5.1 Visualizing Feature Importances](#5.1)
  - [5.2 Interpretation with respect to the task](#5.2)
  - [5.3 Similarities and Differences between the models](#5.3)

[6 Limitations and potential Solutions](#6)
  - [6.1 Limitations with the dataset](#6.1)
  - [6.2 Improvents in the dataset](#6.2)
  - [6.3 Limitations with the model and pipeline](#6.3)
  - [6.4 Alternative Models or pipelines](#6.4)


# Getting Started

To run the notebook locally just install all required packages.

`pip install -r requirements.txt`

  
