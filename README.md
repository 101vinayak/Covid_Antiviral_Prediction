# COVID Drug Prediction Using Seq2Seq Models

This project was developed under the guidance of **Prof. Rahul Katariya** in 2019. It focuses on predicting which antiviral drug works best for COVID-19 based on genome sequencing data. The model reached an impressive **99+% accuracy** and also identified related virus genomes. A novel dataset was created by refining and merging existing antiviral and genome sequence datasets, providing more comprehensive insights into drug efficacy.

---

## Features
- **Model**: Utilizes advanced Seq2Seq neural networks for predicting the most effective antiviral drugs for COVID-19 and related virus genomes.
- **Accuracy**: Achieved over **99% accuracy** in drug prediction.
- **Dataset**: Created a unique dataset combining antiviral and genome sequence data, making it one of the first datasets tailored specifically for this research problem.
- **Research Impact**: Proved which virus genomes share similarities with COVID-19, offering valuable insights for virology research.

---

## Model Overview
The Seq2Seq model is trained on a refined dataset, leveraging **sequence-based predictions** to map genome sequences to antiviral drugs with high accuracy. The model architecture is optimized for handling large genome sequences and extracting key patterns for drug classification.

### Key Technologies
- **TensorFlow / PyTorch** for building the Seq2Seq model.
- **Bi-LSTM** layers for processing long-range genome data sequences.
- **Data preprocessing**: Custom scripts for cleaning and refining the antiviral and genome sequence datasets.

---

## Dataset Creation
The dataset used for this project is a one-of-a-kind compilation that combines multiple open-source antiviral drug data and genome sequences from known viruses. This unique combination allowed for more accurate drug prediction and better generalization to related virus strains.

- **Data Sources**:
    - Public antiviral drug datasets
    - Genome sequencing datasets of known viruses
- **Data Augmentation**: Additional preprocessing steps were applied to improve data quality and enhance model performance.

---

## Results
- **Accuracy**: Reached **99+%** prediction accuracy.
- **Virus Genome Relationship**: Successfully identified viral genomes related to COVID-19, enhancing understanding of viral evolution and drug effectiveness.

---
