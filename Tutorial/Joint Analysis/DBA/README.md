---

![Image](https://github.com/user-attachments/assets/762d2f59-8eb0-40eb-913f-c98ffc2f9c34)

---

🌎 Language:
- 🇺🇸 [English](README.md)
  
---

- GBS is a free software designed for performing statistical analyses applied to quantitative genetics and plant breeding.
- Below, we present a manual and a case study of one of the data analysis procedures carried out in the GBS software.

---

## Joint Analysis of Experiments

---

### Augmented Block Design

---

- For demonstration purposes, the evaluation of 493 treatments of a plant species in three experiments was used, considering specific gravity (GE).

---

<p align="justify">
The figure below shows where the joint analysis procedure for experiments in an augmented block design is located within the software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/4980f9ff-72cf-4c97-8f61-1fb34a4680e7"  alt="Image">
</p>

<p align="justify">
The first step consists of creating a spreadsheet in ".csv" format. This file must contain the identification of experiments in the first column (S1), blocks (Blocos) in the second column, and Treatments (Trat) in the third column. The remaining columns correspond to the evaluated traits, and there may be one or more. The figure below presents the analysis procedure using the example file provided in the software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cf8e5535-1b71-4ffd-a774-6e101bea255d" alt="Image">
</p>

<p align="justify">
After loading the file, the user must access the procedures tab and define the nature of the effects in the statistical model. In this tab, it is also possible to define whether the analysis will consider residual and block variances as homogeneous or heterogeneous. Additionally, if the treatment effect is considered fixed, it is possible to select a mean comparison test (Means tab) to be performed along with the analysis.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/25e14ba4-ec88-4d42-ab3e-741693fd2115" alt="Image">
</p>

<p align="justify">
After defining the analysis settings, the user must click the blue PLAY icon in the upper-left corner to run the analysis. The results will be generated in ".txt" and/or ".xlsx" formats.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e75dab11-d170-494e-84af-f9506c75418d" alt="Image">
</p>

<p align="justify">
The output file in ".txt" format contains various information, with emphasis on fixed and/or random effects tests. The initial part of this file is shown below.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/30925c9c-b1e6-4eef-af45-4e878cca52e1"  alt="Image">
</p>

<p align="justify">
The results of fixed and random effects tests are presented below:
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/9679de13-b458-458a-b03a-37b125b4a2b9" alt="Image">
</p>

<p align="justify">
The individual analysis allowed observing a significant effect of treatments, environments, and treatment × environment interaction for the SG trait. The results file also presents the experiment mean (1071.0711) and the average standard deviation of variances among treatments (5.7084).
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/bf518578-d96d-434c-ac25-ce866e4292bf" alt="Image">
</p>

---
