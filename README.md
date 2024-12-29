# ibm-coursera-deep-learning-and-reinforcement-learning
Course Final Project -  Deep Learning and Reinforcement Learning

## Overview
This project is part of the IBM Coursera course on Deep Learning and Reinforcement Learning. The final project involves the analysis and application of deep learning techniques on a specific dataset.

## Dataset Description
### IQ-OTH/NCCD Lung Cancer Dataset
- **Source**: Collected from the Iraq-Oncology Teaching Hospital/National Center for Cancer Diseases (IQ-OTH/NCCD).
- **Collection Period**: Fall 2019 (over three months).
- **Content**:
  - Total of **1190 images** representing CT scan slices.
  - Images from **110 cases** diagnosed with lung cancer and healthy subjects.
  - Cases are classified into three categories:
    - **Normal**: 55 cases
    - **Benign**: 15 cases
    - **Malignant**: 40 cases
- **Image Format**: Originally collected in DICOM format.
- **Scanner Used**: SOMATOM from Siemens.
- **CT Protocol**:
  - Voltage: 120 kV
  - Slice Thickness: 1 mm
  - Window Width: 350 to 1200 HU
  - Window Center: 50 to 600
  - Breath hold at full inspiration.
- **Ethics**: All images were de-identified. Written consent was waived by the oversight review board. The study was approved by the institutional review board of participating medical centers.

## Data Characteristics
- Each CT scan contains several slices, ranging from **80 to 200 slices**.
- The dataset includes diverse demographics:
  - Gender
  - Age
  - Educational attainment
  - Area of residence
  - Living status
- Participants include employees from the Iraqi ministries of Transport and Oil, as well as farmers and gainers, primarily from the middle region of Iraq (Baghdad, Wasit, Diyala, Salahuddin, and Babylon).

## Usage
This dataset can be used for training deep learning models to classify lung cancer stages and improve diagnostic accuracy.