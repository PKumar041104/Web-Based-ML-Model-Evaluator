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
```

## Project Scope

The initial version of the system focuses primarily on **tabular datasets** and **supervised machine-learning tasks**, particularly:

- Classification
- Regression

The system covers the basic end-to-end workflow of machine-learning model evaluation, beginning with dataset upload and validation and continuing through preprocessing, model selection, training, testing, evaluation, comparison, visualization, and report generation.

### Out of Scope

The initial version does not include:

- Deep-learning model development
- Image processing
- Video processing
- Real-time data evaluation
- Production deployment of trained models

---

## Proposed Technologies

| Technology | Purpose |
|---|---|
| **Python** | Backend programming and machine-learning workflow |
| **Django** | Web application backend/framework |
| **Pandas** | Dataset loading, analysis, and preprocessing |
| **NumPy** | Numerical operations |
| **Scikit-learn** | Machine-learning models, training, testing, and evaluation |
| **HTML** | Web-page structure |
| **CSS** | Web-page styling |
| **JavaScript** | Client-side functionality |
| **Bootstrap** | Responsive user interface |
| **SQLite / PostgreSQL** | Database storage |
| **Chart.js / Plotly.js** | Result visualization |
| **Celery + Redis** | Optional background processing for longer tasks |

---

## System Components

The proposed system consists of the following major components:

1. **Web Interface**
   - Provides the user interface for interacting with the application.

2. **Authentication and User Management**
   - Handles user registration, login, logout, and access control.

3. **Project Management Module**
   - Allows users to create and manage evaluation projects.

4. **Dataset Management Module**
   - Handles dataset upload, validation, preview, and metadata.

5. **Data Preprocessing Module**
   - Performs required preprocessing operations on the dataset.

6. **Model Selection Module**
   - Provides supported classification and regression models.

7. **Model Training Module**
   - Trains the selected machine-learning models.

8. **Testing and Evaluation Module**
   - Tests trained models and calculates appropriate evaluation metrics.

9. **Results Comparison Module**
   - Compares the performance of multiple models.

10. **Visualization Module**
    - Presents evaluation results through suitable charts and graphs.

11. **Reporting Module**
    - Generates downloadable evaluation reports.

12. **Database and Storage**
    - Stores users, projects, dataset metadata, model runs, and evaluation results.

---

## User Roles

### Registered User

A registered user can:

- Upload datasets
- Configure preprocessing
- Select target columns
- Select classification or regression tasks
- Select machine-learning models
- Configure model parameters
- Run model training and evaluation
- Compare model results
- Generate evaluation reports

### Project Guide / Evaluator

The project guide or evaluator can:

- Review the project workflow
- Review system requirements
- Review implementation
- Review model-evaluation results
- Assess the project for academic purposes

### Administrator

The administrator can:

- Manage users
- Manage evaluation projects
- Manage system records
- Monitor operational logs
- Monitor the overall functioning of the application

---

## Project Requirements

The Software Requirements Specification defines:

- **26 Functional Requirements**
- **7 Non-Functional Requirements**
- **2 Security Objectives**
- **6 Security Requirements**
- **2 UML Use-Case Diagrams**
- **Requirements Traceability Matrix (RTM)**
- Acceptance criteria and test-case references

---

## Software Requirements Specification

The first project deliverable is the **Software Requirements Specification (SRS)** document.

### SRS Document

[**View / Download the SRS Document**](./Web_Based_ML_Model_Evaluator_SRS.pdf)

The SRS contains the following major sections:

1. Introduction
2. Overall Description
3. External Interface Requirements
4. System Features (Detailed)
5. Non-Functional Requirements (Detailed)
6. Quality Attributes & Acceptance Tests
7. System Models and Diagrams
8. Requirements Traceability Matrix (RTM)

---

## Repository Structure

The repository currently contains the following:

```text
Web-Based-ML-Model-Evaluator/
│
├── README.md
│
├── Web_Based_ML_Model_Evaluator_SRS.pdf
│
└── Web-Based-ML-Model-Evaluator-Test-Plan.pdf
```

---

## Project Team

| S. No. | Name | SRN | Email |
|---:|---|---|---|
| 1 | **Pratham Kumar** | PES2UG24CS368 | prathamkumar041104@gmail.com |
| 2 | **Nirupama Jayaraman** | PES2UG24CS324 | jnirupama06@gmail.com |
| 3 | **Shreyas Bellad** | PES2UG25CS824 | shreyasbellad2006@gmail.com |
| 4 | **Parinitha Acharya** | PES2UG24CS339 | parinitha.acharya2006@gmail.com |

---

## Individual Contributions

| S. No. | Team Member | SRN | Contribution |
|---:|---|---|---|
| 1 | **Shreyas Bellad** | PES2UG25CS824 | Introduction and Overall Description |
| 2 | **Nirupama Jayaraman** | PES2UG24CS324 | External Interface Requirements and System Features |
| 3 | **Pratham Kumar** | PES2UG24CS368 | Non-Functional Requirements and Quality Attributes & Acceptance Tests |
| 4 | **Parinitha Acharya** | PES2UG24CS339 | UML Use-Case Diagrams and Requirements Traceability Matrix (RTM) |

---

## Academic Deliverable Status

**Current Status:** SRS / Initial Project Deliverable

The current repository contains the **Software Requirements Specification (SRS)** document for the proposed Web Based ML Model Evaluator.

The SRS represents the requirements and planned system design at the initial stage of the project. Implementation and testing resources will be added to the repository as the project progresses.

---

## Future Development

The project will be developed progressively based on the requirements defined in the SRS.

Planned development activities include:

- Web application development
- User authentication implementation
- Dataset upload and validation
- Data preprocessing pipeline
- Machine-learning model integration
- Model training and testing
- Evaluation metric implementation
- Result visualization
- Model comparison
- Report generation
- Database integration
- Functional and non-functional testing
- Security testing
- Final system integration

---

## Documentation

The main project documentation currently available in this repository is:

| Document | Description |
|----------|-------------|
| `README.md` | Project overview and repository documentation |
| `Web_Based_ML_Model_Evaluator_SRS.pdf` | Software Requirements Specification |
| `Web-Based-ML-Model-Evaluator-Test-Plan.pdf` | Software Test Plan and testing strategy |

---

## Institution

**PES University**  
**Department of Computer Science and Engineering (CSE)**  
**Course: UE24CS341A – Software Engineering**  
**5th Semester | Academic Year 2026–27**

---

## License

This project is developed for **academic purposes** as part of the Software Engineering course at PES University.

---

## Acknowledgement

We acknowledge the guidance and support provided by the course coordinator and faculty during the development of this Software Engineering mini project.

---

**Web Based ML Model Evaluator**  
*Software Engineering Mini Project – PES University*
