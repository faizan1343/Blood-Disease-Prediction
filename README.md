# Blood-Disease-Prediction
Blood Health Dataset with 25 features: Glucose, Cholesterol, Hemoglobin, Platelets, WBC, RBC, Hematocrit, MCV, MCH, MCHC, Insulin, BMI, BP, Triglycerides, HbA1c, LDL, HDL, ALT, AST, HR, Creatinine, Troponin, CRP, and Disease. For medical research &amp; ML. Contributions welcome!


## Dataset Description

The dataset contains the following features:
- **Glucose**: Blood sugar level (mg/dL)
- **Cholesterol**: Total cholesterol (mg/dL)
- **Hemoglobin**: Oxygen-carrying protein (g/dL)
- **Platelets**: Blood clotting cells (thousands/µL)
- **White Blood Cells (WBC)**: Immune cells (thousands/µL)
- **Red Blood Cells (RBC)**: Oxygen carriers (millions/µL)
- **Hematocrit**: RBC volume percentage (%)
- **Mean Corpuscular Volume (MCV)**: Average RBC size (fL)
- **Mean Corpuscular Hemoglobin (MCH)**: Hemoglobin per RBC (pg)
- **Mean Corpuscular Hemoglobin Concentration (MCHC)**: Hemoglobin concentration in RBCs (g/dL)
- **Insulin**: Blood insulin level (µU/mL)
- **BMI**: Body Mass Index (kg/m²)
- **Systolic Blood Pressure**: Upper BP value (mmHg)
- **Diastolic Blood Pressure**: Lower BP value (mmHg)
- **Triglycerides**: Blood fat level (mg/dL)
- **HbA1c**: Glycated hemoglobin (%)
- **LDL Cholesterol**: Low-density lipoprotein (mg/dL)
- **HDL Cholesterol**: High-density lipoprotein (mg/dL)
- **ALT**: Alanine aminotransferase (U/L)
- **AST**: Aspartate aminotransferase (U/L)
- **Heart Rate (HR)**: Beats per minute (bpm)
- **Creatinine**: Kidney function marker (mg/dL)
- **Troponin**: Heart damage marker (ng/mL)
- **C-reactive Protein (CRP)**: Inflammation marker (mg/L)
- **Disease**: Target variable (e.g., 0 = healthy, 1 = disease)

## Usage

- **File Format**: CSV (e.g., `blood_health_data.csv`)
- **Applications**: Disease prediction, biomarker analysis, medical ML models
- **Example**:
  ```python
  import pandas as pd
  data = pd.read_csv('blood_health_data.csv')
  print(data.head())
