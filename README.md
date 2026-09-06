# Web Based ML Model Evaluator

## Software Engineering Mini Project

A browser-based application for evaluating supervised machine-learning models on tabular datasets.

---

## Academic Information

| Details | Information |
|---|---|
| **Project Title** | Web Based ML Model Evaluator |
| **Course** | UE24CS341A – Software Engineering |
| **Department** | Department of Computer Science and Engineering (CSE) |
| **Institution** | PES University |
| **Semester** | 5th Semester |
| **Academic Year** | 2026–27 |
| **Project Type** | Software Engineering Mini Project |
| **Deliverable** | Software Requirements Specification (SRS) |
| **SRS Version** | 1.0 |
| **SRS Date** | 06-09-2026 |
| **Course Coordinator** | Sheela Devi M. |
| **Coordinator Email** | sheelam@pes.edu |

---

## Project Overview

The **Web Based ML Model Evaluator** is a browser-based application designed to provide a complete workflow for evaluating supervised machine-learning models on tabular datasets.

The system allows users to upload datasets, validate and preprocess the data, select suitable machine-learning models, train and test the models, evaluate their performance using appropriate metrics, compare multiple models, visualize the results, and generate evaluation reports.

The project is designed to provide a simple web-based platform through which users can perform the basic machine-learning model evaluation workflow without having to manually implement every stage of the process.

---

## Objectives

The main objectives of the project are:

- Provide a web-based interface for machine-learning model evaluation.
- Allow users to upload and validate tabular datasets.
- Provide dataset preview and basic data analysis.
- Allow users to select the target column and machine-learning task.
- Support supervised-learning tasks such as classification and regression.
- Provide data preprocessing and train-test splitting.
- Allow users to select and configure multiple machine-learning models.
- Train and test selected models.
- Calculate appropriate performance metrics.
- Compare the performance of multiple models.
- Provide graphical visualization of evaluation results.
- Allow users to identify a preferred or best-performing model.
- Store previous evaluation results.
- Generate downloadable evaluation reports.

---

## Key Features

### User and Account Management

- User registration
- User authentication
- User login and logout
- Secure session management
- Evaluation project creation and management

### Dataset Management

- CSV dataset upload
- Dataset file validation
- Dataset structure validation
- Dataset preview
- Column and data-type inspection
- Basic dataset statistics
- Target-column selection
- Classification or regression task selection

### Data Processing

- Missing-value handling
- Categorical-data encoding
- Feature scaling
- Data preprocessing
- Train-test dataset splitting

### Machine-Learning Model Evaluation

- Classification model selection
- Regression model selection
- Multiple model selection
- Model parameter configuration
- Model training
- Model testing using unseen test data
- Training status and progress information

### Performance Evaluation

For classification tasks, the system can calculate applicable metrics such as:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

For regression tasks, the system can calculate applicable metrics such as:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² score

### Results and Reporting

- Side-by-side model comparison
- Graphical visualization of model performance
- Preferred/best-performing model selection
- Storage of evaluation results
- Viewing previous evaluation results
- Downloadable evaluation reports

---

## System Workflow

The general workflow of the Web Based ML Model Evaluator is:

```text
User Registration / Login
          ↓
Create Evaluation Project
          ↓
Upload Dataset
          ↓
Dataset Validation
          ↓
Dataset Preview
          ↓
Select Target Column
          ↓
Select Task Type
(Classification / Regression)
          ↓
Data Preprocessing
          ↓
Train-Test Split
          ↓
Select ML Models
          ↓
Configure Model Parameters
          ↓
Train Models
          ↓
Test Models
          ↓
Evaluate Performance
          ↓
Compare Model Results
          ↓
Visualize Results
          ↓
Select Preferred Model
          ↓
Generate Evaluation Report
