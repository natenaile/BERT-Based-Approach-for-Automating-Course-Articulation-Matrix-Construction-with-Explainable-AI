# BERT-Based Approach for Automating Course Articulation Matrix Construction with Explainable AI.

## Overview

This project automates the construction of a **Course Articulation Matrix (CAM)**, which quantifies the alignment between Course Outcomes (COs) and Program Outcomes (POs) or Program-Specific Outcomes (PSOs). The alignment is crucial for ensuring curriculum coherence and assessing the effectiveness of educational programs. The project employs machine learning and transfer learning models to automate this process with high performance and interpretability.

### Objectives:
- Develop a system to assess the alignment between COs and POs/PSOs.
- Experiment with traditional machine learning classifiers and pretrained BERT-based models.
- Use Explainable AI techniques to enhance model transparency.

## Methodology

1. **Data Collection & Preprocessing**:  
   The project uses textual data representing CO and PO/PSO pairs, labeled with numerical values (0, 1, 2, 3) to represent the degree of alignment.

2. **Models Used**:
   - **Traditional Machine Learning**: Decision Tree, Random Forest, XGBoost.
   - **Transfer Learning with BERT-based Models**: BERT Base, DistilBERT, ALBERT, and RoBERTa.

3. **Explainable AI**:  
   **Local Interpretable Model-agnostic Explanations (LIME)** is applied to provide insights into the decision-making process, enhancing interpretability.

5. **Performance Evaluation**:
   Models are evaluated based on accuracy, precision, recall, and F1-score.

## Results

The system achieves the following performance metrics:
- **Accuracy**: 98.66%
- **Precision**: 98.67%
- **Recall**: 98.66%
- **F1-score**: 98.66%
## Automated CAM for a randomly selected course from CBIT, India, showing one misclassified cell highlighted in orange.
![image7](https://github.com/user-attachments/assets/a36005e5-4249-4127-b641-80b5ee5ebfee)

These results highlight the effectiveness of using BERT-based transfer learning models for the automated generation of CAMs, with a focus on high performance and model interpretability.

## Key Features

- **High Performance**: The BERT-based models outperform traditional classifiers, achieving near-perfect evaluation metrics.
- **Interpretability**: LIME provides transparency into the model's decision-making process, making the system more understandable.
- **Scalable**: The system can be adapted to handle different educational curricula and be used in various academic settings.

## System Specifications

The experiments and models were run on the following system specifications:

- **CPU**: Intel i9
- **RAM**: 16 GB
- **GPU**: NVIDIA RTX A2000
- **Storage**: 1 TB HDD

## Installation & Usage

### 1. Running the Project in Jupyter Notebook

To run this project in **Jupyter Notebook**, follow these steps:

1. Clone or download this repository to your local machine.
2. Install the necessary dependencies (listed below).
3. Open the notebook in **Jupyter Notebook**.
4. Run the cells sequentially to execute the code and generate the results.

### 2. Dependencies

The notebook requires the following Python libraries:

- **PyTorch**
- **Hugging Face Transformers**
- **Scikit-learn**
- **LIME**
- **Matplotlib**
- **Pandas**
- **NumPy**

You can install these dependencies by running the following command in your terminal or within a Jupyter Notebook cell:

```bash
pip install transformers torch scikit-learn lime matplotlib pandas numpy
