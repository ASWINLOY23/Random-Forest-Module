# Enterprise Random Forest Analytics Studio

An enterprise-style machine learning dashboard built using **R Shiny** and **Random Forest** for predictive analytics, classification modeling, interactive model evaluation, and intelligent decision support workflows.

This application enables users to upload datasets, configure predictor variables dynamically, train Random Forest classification models, evaluate model performance using ROC/AUC metrics, analyze variable importance, and generate downloadable prediction outputs through a professional analytics dashboard.

---

# Features

## Dataset Management

* Upload CSV datasets dynamically
* Interactive target and predictor variable selection
* Optional unique identifier selection
* Automatic missing value handling using `na.omit()`

## Random Forest Machine Learning Workflow

* Random Forest binary classification modeling
* Configurable train-test split
* Prediction probability generation
* Bootstrap sampling support
* Dynamic predictor selection

## Hyperparameter Configuration

* Adjustable number of trees (`ntree`)
* Configurable variables tried at each split (`mtry`)
* Minimum node size configuration (`nodesize`)
* Maximum nodes per tree configuration (`maxnodes`)
* Bootstrap sampling toggle (`replace`)

## Model Evaluation

* ROC Curve visualization
* AUC score calculation
* Confusion Matrix generation
* Accuracy metric calculation
* Sensitivity metric calculation
* Optimal threshold detection

## Variable Importance Analytics

* Random Forest variable importance visualization
* Feature contribution analysis
* Interactive model interpretability support

## Interactive Dashboard

* Enterprise-style dashboard UI
* Interactive Plotly visualizations
* KPI performance cards
* Responsive analytics interface using `shinydashboard`

## Prediction Export

* Download prediction outputs as CSV
* Includes probabilities and predicted classes

---

# Tech Stack

| Technology     | Purpose                    |
| -------------- | -------------------------- |
| R              | Programming Language       |
| Shiny          | Web Application Framework  |
| shinydashboard | Dashboard UI               |
| randomForest   | Ensemble Learning Engine   |
| Plotly         | Interactive Visualizations |
| caret          | Model Evaluation           |
| pROC           | ROC & AUC Analysis         |
| DT             | Interactive Data Tables    |
| shinyWidgets   | Enhanced UI Components     |

---

# Required Packages

```r
install.packages(c(
  "shiny",
  "shinydashboard",
  "shinyjs",
  "shinycssloaders",
  "shinyWidgets",
  "pROC",
  "caret",
  "DT",
  "plotly",
  "randomForest"
))
```

---

# Running the Application

```r
library(shiny)

runApp()
```

Or directly run:

```r
shiny::runApp()
```

---

# Project Structure

```text
├── app.R
├── README.md
├── LICENSE
├── sample_data.csv
└── screenshots/
```

---

# Application Workflow

1. Upload CSV dataset
2. Select optional ID column
3. Choose target variable
4. Select predictor variables
5. Configure Random Forest hyperparameters
6. Train Random Forest classification model
7. Evaluate model performance
8. Analyze variable importance
9. Download prediction results

---

# Example Use Cases

* Healthcare Risk Prediction
* Fraud Detection
* Customer Churn Modeling
* Insurance Analytics
* Credit Risk Scoring
* Marketing Response Prediction
* Clinical Outcome Prediction
* Business Intelligence Analytics

---

# Highlights

* Enterprise-style machine learning dashboard
* Interactive Random Forest analytics workflow
* Variable importance analysis
* Dynamic hyperparameter configuration
* Interactive ROC visualization
* Downloadable prediction outputs
* Modern responsive UI design

---

# Future Enhancements

Potential future improvements:

* Cross-validation support
* Hyperparameter optimization
* SHAP explainability integration
* Multi-class classification support
* Model persistence
* Database integration
* User authentication
* Cloud deployment automation

---

# Deployment Options

This application can be deployed using:

* ShinyApps.io
* Posit Connect
* Docker
* AWS
* Azure
* Google Cloud Platform

---

# Author

Developed using R Shiny and Random Forest for enterprise predictive analytics and interactive machine learning workflows.

---

# Copyright

Copyright © 2026 Aswin Sankar

All rights reserved.

This source code may not be copied, modified, distributed, sublicensed, sold, or used commercially without explicit written permission from the author.

Commercial licensing is available for organizations, businesses, consultants, and deployment usage.

---

# Support

If you found this project useful:

* Star the repository
* Share feedback
* Connect for collaboration opportunities
