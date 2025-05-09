# Azure DP-100 Project Repository Overview

This repository presents the full implementation and automation of a predictive machine learning solution developed on Microsoft Azure Machine Learning. It demonstrates core competencies required for the **DP-100: Designing and Implementing a Data Science Solution on Azure** certification.

## 🔗 Main Project
- **[Azure DP-100 - Ice Cream Sales Forecasting](https://github.com/AndreLuiz-Cardoso/Data-Science/tree/main/Azure/Azure%20DP-100/Project-1)**  
  A complete end-to-end project using Azure ML Studio and AutoML to predict ice cream sales based on temperature. It includes both a manual pipeline and an automated model selection and evaluation process.

## 📁 Directory Structure
```
project-folder/
├── img/                            # Visual assets (screenshots of pipeline, metrics, experiments)
│   ├── pipeline.png
│   ├── 01.png
│   ├── 02.png
│   └── 03.png
├── outputs/                        # Outputs from Azure experiments (if generated)
├── automl_driver.py               # Driver script used by AutoML for remote run execution
├── cyan_truck_ptggd842xf.jsonl    # Sample logging or tracking artifact
├── definition.json                # Run definition for Azure ML experiment
├── definition_original.json       # Original definition before transformation
├── full_training_dataset.df.parquet  # Full training dataset output by AutoML
├── model.pkl                      # Serialized trained model (VotingEnsemble)
├── python_env.yaml                # Python environment configuration
├── requirements.txt               # Required Python packages
├── conda.yaml                     # Conda environment for full reproducibility
├── MLmodel                        # MLflow-compatible model metadata
├── verifier_results.json          # AutoML run validation and guardrail results
├── X_valid.pkl                    # Test features set
├── y_valid.pkl                    # Test labels
├── sample_weight_valid.pkl        # Sample weights for validation set
└── README.md                      # Project summary and technical write-up
```

## 📘 Related Skills Demonstrated
- Azure ML Designer (Pipelines)
- Automated Machine Learning (AutoML)
- Model Evaluation and Metrics
- MLflow Logging
- Environment Management (YAML, Conda)
- Dataset Management in Azure

---

> This repository was developed as part of the preparation for the **Microsoft Certified: Azure Data Scientist Associate (DP-100)** certification.

**Author:** André Luiz Cardoso  
**Date:** May 9, 2025
