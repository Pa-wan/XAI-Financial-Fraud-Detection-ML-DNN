# Explainable AI-Driven Financial Transaction Fraud Detection Application using Machine Learning and Deep Neural Networks
######################################
## Introduction

<p align = 'justify' > Artificial Intelligence (AI) has entered the business mainstream opening new opportunities to solve the most complex business problems. In the Covid-19 pandemic, the use of online payments has skyrocketed, and the world is making an inexorable shift toward digital transformation by using more cards and mobile apps instead of cash. </p>

<p align = 'justify' > As per Statista research, Visa is the market leader among digital payment processors in the world with more than $10 trillion in transactions, followed by Apple Pay and Alipay. In UK E-commerce, Visa and Mastercard are the most frequently used payment options. These payment options are available from 98% of the top 500 online retailers in 2020. </p>

## Impact of AI in Finance & Banking

<p align = 'justify' >The finance and banking industry has benefited from digital technologies like AI, creating a new discipline of FinTech. AI is projected to save the banking industry approx $1 trillion by 2030 and $447 billion by 2023. </p>

<p align = 'justify' >AI is used in FinTech to create solutions to the problems that traditional finance and banking sectors like Fraud Detection, Risk Management, Investment Management, Predictive Analytics and Anti-Money Laundering. </p>

<p align="center" width="100%">
<img alt="GIF" src="https://user-images.githubusercontent.com/31254745/191377492-9b827999-aba9-4dc7-8adf-fdb1b6c8fb19.png">
</p>

## Financial Transaction Fraud Detection

<p align = 'justify' >While digitisation creates opportunities for development and growth, it also attracts cybercriminals and fraudsters for financial fraud which has become a major business problem in the financial and banking industry. </p>

<p align = 'justify' >Fraud losses increased by 30% and fraudsters have stolen £754 million from bank financial transactions and 76% of CC fraud losses in the UK were due to Card-not-Present (CNP) totalling £470.2 million (UK Finance, 2021).</p>
<p align="center" width="100%">
<img alt="GIF" src="https://user-images.githubusercontent.com/31254745/191378636-97f1fe09-018e-4be3-a025-4a2330ded381.png">
</p>

## Research Problem

### Can we 'trust AI' just because it is very accurate?

<p align = 'justify' > In financial fraud detection, several ML methods have been applied to detect fraudulent behaviour on financial data. Most of the current fraud detection systems are based on black-box models, so it becomes more difficult to understand and explain predictions of these systems to business decision-makers or non-AI expert users.</p>

<p align = 'justify' > This “black-box” challenge is one of the biggest roadblocks preventing financial services and the banking industry from operationalising their AI strategies into production. Fortunately, Explainable AI (XAI), a human-centric AI helps to boost end-user confidence, transparency and trust by providing explanations of AI models that are more understandable to humans for better business decision-making.</p>

<p align = 'justify' >This research project aims to fill the gap of the lack of explainability of complex black box AI models in financial transaction fraud detection.</p> 

## Research Aim and Objectives

<p align = 'justify' >This research study aims to implement an “Explainable AI (XAI)-driven Interface and a Proof of Concept (POC) Web Application for Financial Transaction Fraud Detection using Machine Learning and Deep Neural Networks” in the Financial Services and Banking industry. </p>

To achieve this aim, the below four objectives are stated as follows:

- **Objective 1:** Build a Robust Classification engine to classify a financial transaction as fraudulent or legitimate by applying five ML algorithms, and two DNN algorithms.
- **Objective 2:** Evaluate the performance of all model results using metrics like Accuracy, AUC-ROC Score, Confusion Matrix, Recall, Precision, F1 Score, AUC-ROC Curve and Precision-Recall Curve.
- **Objective 3:** Implement five Explainable AI (XAI) methods and Explainability Interface for improving trust and model explainability on best-performing model results obtained in objective 2.
- **Objective 4:** Develop Proof of Concept (POC) as a front-end web application for business decision-makers to generate business value and make real-time predictions on fraud detection.

## Explainable AI (XAI)

<p align = 'justify' > Explainable AI (XAI) is an emerging branch of AI that focuses on converting complex 'black-box' AI algorithms and system outputs into clearly understandable, trustable, or so-called 'white-box' AI algorithms.</p>

<p align = 'justify' >With XAI, black-box AI models are more explainable, intuitive, and understandable to business decision-makers without sacrificing performance or prediction accuracy.</p>

### *"While Intelligence is the primary deliverable of AI, Explainability is the fundamental need of an AI product."*

<p align="center" width="100%">
<img alt="GIF" src="https://user-images.githubusercontent.com/31254745/191379681-85254992-1c9a-4e3d-b944-f5d6ddb24152.png">
</p>

### XAI - How does it help Business Users?

![image](https://user-images.githubusercontent.com/31254745/191379930-2ee1c7b2-10ec-430a-afa9-90185dcfa653.png)

## Research Methodology

The proposed design process is inspired by the CRISP-DM process to accomplish the aim and four research objectives formulated in the research framework will be discussed. 

Model explainability is one stage that is involved in the design process.  Business organisations may better comprehend and manage their AI systems with the aid of explainable AI. Therefore, to guarantee that AI project gives business organisations the necessary benefits, make sure the AI solution is explainable. 

![image](https://user-images.githubusercontent.com/31254745/191380128-8a619a02-4378-44b7-9f99-ece284aca6f0.png)

## Research Methods

![image](https://user-images.githubusercontent.com/31254745/191380294-b1b94541-f855-4f1a-8c7f-beffef920300.png)

## Research Project Workflow

![image](https://user-images.githubusercontent.com/31254745/191380390-6b88bcab-93e5-4cb3-af34-86e2712f2a6a.png)

## Data Preparation

In this study, we have chosen a dataset of real financial transactions provided by Vesta Corporation, the world's top payment service provider and the IEEE Computational Intelligence Society (IEEE-CIS) cooperated to find the best fraud prevention strategies for the banking and financial sectors. Data is divided into two 'identify' and 'transaction' files, which are connected by a transactionid.

- Transaction.csv: It contains transactional information to be used in model training. The transaction dataset has 590540 rows/data samples and 394 columns/features. 
- Identity.csv: It contains information about the identity of the payer and the merchant between whom the transaction was made. It has 144233 rows/data samples and 41 columns/features.

## Optimisation of Memory and Run-time

![image](https://user-images.githubusercontent.com/31254745/191380568-4aaf7d6a-8e4c-4384-adcc-80ff5e08fe17.png)

## XAI Implementation

### 1. SHAP (Shapley Additive Explanations)

<p align="center" width="100%">
<img alt="GIF" src="https://user-images.githubusercontent.com/31254745/191380674-eada5c89-a0bc-462a-8307-07cc07974653.png">
</p>

###  2. LIME (Local Interpretable Model-Agnostic Explanations)

![image](https://user-images.githubusercontent.com/31254745/191380832-c0859780-c24a-45e0-9829-5a6518cdb8dd.png)

### 3. SHAPASH

<p align="center" width="100%">
<img alt="GIF" src="https://user-images.githubusercontent.com/31254745/191380886-e65c89d6-0e0c-4105-8b2b-daeeb2d405dd.png">
</p>


## Proof-of-Concept (POC) Demonstration

Web App Link : https://chaithanyavamshi-fraud-predictor-app-streamlit-app-qy0hjs.streamlitapp.com/

![image](https://user-images.githubusercontent.com/31254745/191382290-cee8113d-0c7d-407d-b1b0-fa7c628cf780.png)

## Results

<p align = 'justify' >When it comes to identifying fraudulent transactions, boosting tree algorithms like Light GBM and XGBoost outperform ensemble tree-based models like Decision Tree and Random Forest as well as linear models like Logistic Regression.</p>

<p align = 'justify' >When considering all the evaluation measures, after hyperparameter tuning light GBM models outperform all other ML and DNN models with 98.27% Accuracy, AUC-ROC score of 0.96 and F1-score of 0.70.</p>

<p align = 'justify' >In the project, Light GBM, and XGBoost outperform ANN and CNN-based fraud detection models in terms of performance. This is understandable given the research demonstrating the superior performance of tree-based ensemble models over DNN models on tabular data.</p>

<p align="center" width="100%">
<img alt="GIF" src="https://user-images.githubusercontent.com/31254745/191382637-26c54d01-a548-46a9-868b-051dff5ab4a7.png">
</p>

## Conclusion 

<p align = 'justify' >This research project tackled and filled the gap of the lack of explainability by implementing an Explainable AI (XAI)-driven Interface and a Proof of Concept (POC) Web Application for Financial Transaction Fraud Detection using Machine Learning (ML) & Deep Neural Network (DNN).</p>

<p align = 'justify' >Therefore, XAI-driven financial transaction fraud detection system predictions can be operationalized into production with greater confidence, trust and transparency. This will save a surplus revenue, better forecasts, and greater understandability, reduce uncertainty in business decisions and prevent fraud in financial services and the banking industry.</p>











