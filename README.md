# A Synthetic, Clinically Inspired Neonatal Dataset for Multi-Class Disease Prediction and Trust-Aware Machine Learning

## Authors

**Sanjay Makwana**  
Research Scholar, Indus University, Gujarat, India  
ORCID: https://orcid.org/0009-0005-1584-6257  

**Dr. Seema Mahajan**  
Research Guide, Head of Department (Computer Engineering)  
Indus University, Gujarat, India


## Dataset Overview
This repository provides a **synthetic, clinically inspired neonatal dataset** designed to support **methodological research in machine learning**, particularly in the areas of **multi-class disease prediction**, **trust-aware modeling**, **uncertainty estimation**, and **confidence-aware decision systems**.

The dataset has been developed as part of a PhD research project focusing on the design of **robust, transparent, and reliability-aware machine learning frameworks** for neonatal health applications. It is intended as a **research-enabling resource**, not as a clinically validated benchmark.

---

## Key Characteristics
- **Synthetic data** (no real patient information)
- **Clinically inspired feature design**
- **Multi-class neonatal disease labels (9 classes)**
- Supports research in:
  - Trust-aware and confidence-aware ML
  - Uncertainty estimation (e.g., entropy-based analysis)
  - Probability calibration
  - Stage-wise and progressive modeling (documented, not enforced)

---

## Dataset Structure
```
Synthetic_Neonatal_Dataset_Trust_Aware_ML/
│
├── data/
│ └── synthetic_neonatal_data.csv
│
├── metadata/
│ └── feature_stage_mapping.csv
│
├── README.md
└── LICENSE
```

---

## Data File Description

### `synthetic_neonatal_data.csv`
- Each row represents a **synthetic neonatal case**
- Columns represent **maternal, birth-related, and postnatal features**
- One column represents the **target disease category**

### Target Column
- **Column name:** `Predicted_Disease`
- This column represents the **synthetic ground-truth disease label** assigned during data generation.
- Despite the name, it does **not** represent model predictions.

---

## Disease Classes
The dataset includes **nine synthetic neonatal disease categories**:

1. Other Respiratory Conditions  
2. Birth Asphyxia and Hypoxic-Ischemic Encephalopathy (HIE)  
3. Low Birth Weight (LBW) and Related Conditions  
4. Meconium-Stained Liquor (MSL) and Related Conditions  
5. Infections and Sepsis  
6. Metabolic and Genetic Disorders  
7. Respiratory Distress Syndrome (RDS) and Related Conditions  
8. Hyperbilirubinemia and Neonatal Jaundice  
9. Other Conditions  

These categories are **clinically inspired groupings** and do not correspond to ICD codes or real-world diagnostic labels.

---

## Feature Documentation and Clinical Stages

The dataset is provided as a **single consolidated file**.  
To support research on **stage-wise and progressive decision-making**, an auxiliary metadata file is included:

### `feature_stage_mapping.csv`
This file documents:
- Feature names
- Their associated **clinical availability stage**
- A short neutral description of each feature

### Clinical Stages (Conceptual)
- **Stage 1:** Maternal and antenatal information
- **Stage 2:** Delivery and birth-related observations
- **Stage 3:** Postnatal vitals, laboratory indicators, and interventions

These stages are provided **for research guidance only** and do not impose any constraints on how the dataset must be used.

---

## Intended Use
This dataset is intended for:
- Methodological machine learning research
- Multi-class classification experiments
- Trust-aware and uncertainty-aware modeling
- Confidence-based decision logic (e.g., accept–defer systems)
- Calibration and reliability analysis
- Educational and benchmarking purposes using synthetic data

---

## Not Intended Use
This dataset **must not** be used for:
- Clinical diagnosis or treatment decisions
- Real-world neonatal care or deployment
- Medical device development
- Regulatory or policy decision-making

---

## Ethical Considerations and Privacy
- The dataset is **entirely synthetic**
- No real patient data is included
- No identifiable or sensitive personal information is present
- No ethical approval is required for its use

The dataset is designed to encourage **open and reproducible research** while maintaining strict ethical and privacy safeguards.

---

## Citation
If you use this dataset in your research, please cite it as:

> Makwana, S., & Mahajan, S. (2026). *A Synthetic, Clinically Inspired Neonatal Dataset for Multi-Class Disease Prediction and Trust-Aware Machine Learning*. Zenodo. https://doi.org/XXXXX

(The DOI will be updated after publication.)



---

## License
This dataset is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

You are free to use, share, and adapt the dataset, provided appropriate credit is given.

---

## Acknowledgment
This dataset was developed as part of doctoral research focused on advancing **trustworthy and transparent machine learning frameworks** for neonatal health applications.
