# EM Algorithm and Its Applications: MRI Image Segmentation

## Overview

This project is a group academic study that implements the Expectation–Maximization (EM) algorithm for MRI image segmentation. The objective is to classify MRI images into tumor and non-tumor regions using probabilistic modeling and iterative parameter estimation.

The study combines image preprocessing techniques with statistical learning methods to improve segmentation accuracy.

---

## Project Year: 2024

## Objectives

* Apply EM algorithm for image segmentation
* Preprocess MRI images for analysis
* Perform contrast enhancement and noise reduction
* Model pixel intensities using probabilistic distributions
* Classify regions into tumor and non-tumor classes

---

## Data

The dataset consists of MRI scan images used for segmentation tasks, including:

* Brain MRI images
* Pixel intensity distributions
* Labeled tumor and non-tumor regions (where available)

---

## Methodology

### Image Preprocessing

* Noise removal
* Contrast enhancement
* Normalization of pixel intensities

### EM Algorithm

* Initialization of parameters
* Expectation step (E-step) for probability estimation
* Maximization step (M-step) for parameter updates
* Iterative convergence until stability

### Classification

* Probabilistic assignment of pixels
* Tumor vs non-tumor segmentation

---
![Tumor Segmentation](Latex/Images/Figure_2%20Segmentation%20into%20tumor%20and%20non%20tumor%20region.png)

**Figure 2: Segmentation into Tumor and Non-Tumor Region**

![Final Output](Latex/Images/Figure_3_Final%20Output.png)

**Figure 3: Final Output**
## Key Contributions

* Implemented EM algorithm for medical image segmentation
* Developed probabilistic modeling framework for MRI data
* Improved segmentation using preprocessing techniques
* Performed tumor detection using unsupervised learning

---

## Tools and Technologies

* Python / R
* NumPy, SciPy
* Image processing libraries
* Statistical modeling
* Expectation–Maximization algorithm

---

## Repository Structure

```text id="em_struct"
README.md
Em.pdf
Latex/                   
Latex/Codes/
Latex/Images/
```

---

## Authors and Contributions

This project was completed as a group academic project under faculty supervision.

### Authors

* Rahul Ganguly
* [Other authors as listed in the project report]

---

### Individual Contributions (Rahul Ganguly)

Rahul Ganguly contributed to:

* Implementation of the EM algorithm
* Image preprocessing and contrast enhancement
* Probabilistic modeling of pixel intensities
* Iterative parameter estimation using EM steps
* Tumor vs non-tumor classification logic
* Visualization and result interpretation
* Preparation of analytical sections of the report

---

## Project Summary

This study demonstrates the application of the Expectation–Maximization algorithm for MRI image segmentation, enabling probabilistic classification of tumor and non-tumor regions using statistical learning techniques.
