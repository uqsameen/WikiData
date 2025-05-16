# UNBIASED_TOXICITY

This repository contains code and data for analyzing and mitigating bias in toxicity detection models.

## Project Description

This project focuses on developing and evaluating various machine learning models for identifying toxic content while minimizing unintended biases. We explore different model architectures (LR, CNN) and mitigation strategy to improve fairness and accuracy.

## Repository Structure

* **ALL_RUT_Models:** Contains generic code for all the ML models.
* **RUT_Utils:**  Utility scripts and helper functions.
* **testing_data:**  Dataset used for evaluating model performance.
* **training_data:** Dataset used for training the models.
* **Generic_Evaluations.ipynb:**  General model evaluations.
* **model_03_LR_biased.ipynb:**  Logistic Regression model trained on biased data.
* **model_03_LR_debiased.ipynb:** Logistic Regression model trained on debiased data.
* **model_05_CNN_George_biased.ipynb:** CNN model (George architecture) trained on biased data.
* **model_05_CNN_George_debiased.ipynb:** CNN model (George architecture) trained on debiased data.
* **ROC_Evaluations_Classifiers.ipynb:**  Evaluations for different classifiers.
* **ROC_Evaluations_Situational.ipynb:** Evaluations based on situational testing.
* **SR_CNN_George.ipynb:** Situational testing of the CNN_George model.
* **SR_LR.ipynb:** Situational testing of the Logistic Regression model.


## Getting Started

1. **Clone the repository:** `git clone https://github.com/uqsameen/WikiData.git`
2. **Run the Jupyter notebooks:**  Open and run the notebooks in your preferred environment (e.g., Jupyter Notebook, Google Colab).
