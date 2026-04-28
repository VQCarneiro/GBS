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

### Lattice Designs (Square, Rectangular, and Alpha Lattice)

---

- For demonstration purposes, the evaluation of 49 treatments of a plant species in two experiments was used, considering bacterial blight severity (SCB).

---

<p align="justify">
The figure below shows where the joint analysis procedure for experiments in lattice designs is located within the software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a62a2eb4-7e66-4a5a-bc12-1dcc27fd6088"  alt="Image">
</p>

<p align="justify">
The first step consists of creating a spreadsheet in ".csv" format. This file must contain the identification of experiments in the first column (Amb), repetitions (REP) in the second column, blocks in the third column (Blocos), and Treatments (Trat) in the fourth column. The remaining columns correspond to the evaluated traits, and there may be one or more. The figure below presents the analysis procedure using the example file provided in the software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cc5f0b7a-24ec-4537-b685-297e2438d05e" alt="Image">
</p>

<p align="justify">
After loading the file, the user must access the procedures tab and define the nature of the effects in the statistical model. In this tab, it is also possible to define whether the analysis will consider residual and block variances as homogeneous or heterogeneous. Additionally, if the treatment effect is considered fixed, it is possible to select a mean comparison test (Means tab) to be performed along with the analysis.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ac42f32f-1b6c-4b62-8652-f5d04ec5bf4c" alt="Image">
</p>

<p align="justify">
After defining the analysis settings, the user must click the blue PLAY icon in the upper-left corner to run the analysis. The results will be generated in ".txt" and/or ".xlsx" formats.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a0014728-edbb-4630-a2a1-90dfd982631a" alt="Image">
</p>

<p align="justify">
The output file in ".txt" format contains various information, with emphasis on fixed and/or random effects tests. The initial part of this file is shown below.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/35d19606-281b-4fc2-b81a-9a9db24b895b"  alt="Image">
</p>

<p align="justify">
The results of fixed and random effects tests are presented below:
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b48ddf9e-18d6-4e82-b922-b68853a038ad" alt="Image">
</p>

<p align="justify">
The individual analysis showed a significant effect of treatments and environments. However, no significant effect of the treatment × environment interaction was observed for the SCB trait. The results file also presents the experiment mean (6.0510), heritability (0.5938), and accuracy (0.7627).
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a98ed9d3-5c81-47fc-9ffc-07ba9ac8cbd1" alt="Image">
</p>

---
