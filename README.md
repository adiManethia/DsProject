# 🍷End-to-End Machine Learning Project: Wine Quality Prediction

Welcome to the **Wine Quality Prediction** project! This repository contains an end-to-end machine learning pipeline built using the **Wine Quality Dataset**. The project leverages tools like **MLflow**, **DagsHub**, and **Flask** to create a robust and interactive solution for predicting wine quality.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Workflow](#project-workflow)
- [Folder Structure](#folder-structure)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [License](#license)

---

## Project Overview
This project demonstrates the complete lifecycle of a machine learning solution:
1. **Data Ingestion**: Collect and preprocess the Wine Quality dataset.
2. **Model Training**: Train machine learning models to predict wine quality.
3. **Model Evaluation**: Evaluate the model's performance using metrics and track experiments with **MLflow** and **DagsHub**.
4. **Deployment**: Deploy the model using **Flask** to provide a simple and interactive user interface.

---

## Features
- **End-to-End ML Pipeline**: From data ingestion to deployment.
- **Experiment Tracking**: Integrated with **MLflow** and **DagsHub** for tracking experiments and model performance.
- **Interactive UI**: A simple Flask-based web interface for users to input data and get predictions.
- **Configurable Workflow**: YAML-based configuration for easy customization.

---

## Tech Stack
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Flask
- **Experiment Tracking**: MLflow, DagsHub
- **Deployment**: Flask
- **Version Control**: Git and GitHub
- **Containerization**: Docker

---

## Project Workflow
The project is divided into the following stages:
1. **Data Ingestion**: Load and preprocess the dataset.
2. **Data Validation**: Validate the dataset schema using `schema.yaml`.
3. **Data Transformation**: Perform feature engineering and preprocessing.
4. **Model Training**: Train and save the model.
5. **Model Evaluation**: Evaluate the model and log metrics using MLflow.
6. **Deployment**: Deploy the model using Flask for real-time predictions.

### Steps to Run the Workflow
1. Update the following configuration files:
   - `config.yaml`
   - `schema.yaml`
   - `params.yaml`
2. Implement the pipeline components in the `src` directory.
3. Run the pipeline using `main.py`.

---

## Folder Structure

```
DsProject/
├── .github/workflows/ # CI/CD workflows
├── config/ # Configuration files (config.yaml, schema.yaml, params.yaml)
├── research/ # Notebooks for exploratory data analysis
├── src/datascience/ # Source code for ML pipeline
├── templates/ # HTML templates for Flask UI
├── app.py # Flask application
├── main.py # Entry point for the ML pipeline
├── requirements.txt # Python dependencies
├── Dockerfile # Docker configuration
├── setup.py # Package setup
└── README.md # Project documentation
```

## Setup Instructions
1. Clone the repository:
   ```
   git clone https://github.com/adiManethia/DsProject.git
   cd DsProject
   ```
2. Create a virtual environment and activate it:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Run the pipeline:
   ```
   python main.py
   ```
5. Start the Flask app:
   ```
   python app.py
   ```

## Usage
* **Experiment Tracking** : Use MLflow and DagsHub to monitor model performance.
* **Web Interface** : Input wine features through the Flask UI to get quality predictions.

## License

This project is licensed under the GPL-3.0 License.

Feel free to contribute to this project by submitting issues or pull requests. 




