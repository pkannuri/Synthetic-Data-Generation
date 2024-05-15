# Synthetic-Data-Generation
Enhancing Patient Privacy with Synthetic Data Generation via Python

## Project Overview
This project, conducted by Purdue University's MSBAIM 2024 cohort, focuses on enhancing patient privacy through synthetic data generation. Our goal is to balance the utility of healthcare data with rigorous privacy standards, allowing for safe and responsible data sharing within the healthcare industry.

## Objectives
- To develop synthetic data generation methods that preserve the statistical characteristics and predictive ability of real patient data while ensuring strong privacy guarantees.
- To assist healthcare providers in utilizing data analytics without compromising patient confidentiality.

## Dataset Description
The synthetic dataset used mimics real patient data adhering to HL7 FHIR standards, encompassing clinical information, healthcare utilization, and patient demographics:
- **Clinical Information:** Includes medical history, procedures, immunizations, and observations.
- **Healthcare Utilization:** Details encounters, medications, and care plans.
- **Patient Demographics:** Covers essential demographics such as age, gender, race, and ethnicity.

## Methodology
- **Data Preprocessing:** Involves data cleaning, handling missing values, and feature engineering to prepare the dataset for synthetic data generation.
- **Synthetic Data Generation Techniques:** Utilizes various models like DataSynthesizer, VAE, Gaussian Copula, CTGAN, and Copula GAN to generate synthetic datasets.
- **Model Evaluation:** Includes quantitative comparison and privacy verification to ensure the synthetic data meets privacy and utility standards.

## Key Technologies
- **SQL** for data manipulation and queries.
- **Python** for data processing and machine learning models.
- **Tableau** for data visualization.

## Results
Our evaluations indicate that CTGAN provides the best balance between data utility and privacy, closely replicating the predictive performance of real data models while maintaining a reasonable level of privacy.
