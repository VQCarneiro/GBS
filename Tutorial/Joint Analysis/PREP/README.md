---

![Image](https://github.com/user-attachments/assets/762d2f59-8eb0-40eb-913f-c98ffc2f9c34)

---

🌎 Language:
- 🇧🇷 [Portuguese](README_pt-BR.md)

---

- GBS is free software designed to perform statistical analyses applied to quantitative genetics and plant breeding.
- Below, we present a manual and a case study of one of the data analysis procedures carried out in the GBS software.

---

## Joint Analysis of Experiments

---

### Partially Replicated Design

---

- For demonstration purposes, an evaluation of 319 treatments of a plant species was conducted across two experiments for specific gravity (SG).

---

<p align="justify">
The figure below shows where to find the joint analysis procedure for experiments in a Partially Replicated Design within the software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/7320db99-3697-47d8-8594-7bf7ca8e07b4" alt="Image">
</p>

<p align="justify">
The first step is to create a spreadsheet in ".csv" format. This file must include experiment identification in the first column (Year), rows (Row) in the second column, columns (Column) in the third column, and Treatments (ID) in the fourth column. The remaining columns correspond to the evaluated traits, and there may be one or more. The figure below shows the analysis procedure using the example file provided in the software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d625823d-4454-4742-b337-f40760ed628f" alt="Image">
</p>

<p align="justify">
After loading the file, the user should access the procedures tab and define the nature of the effects in the statistical model. In this tab, it is also possible to specify whether residual and block variances will be considered homogeneous or heterogeneous. Additionally, if the treatment effect is considered fixed, it is possible to select a mean comparison test (Means tab) to be performed along with the analysis.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d9309ae9-a552-4a80-aae7-d1dae3ccdcc2" alt="Image">
</p>

<p align="justify">
After defining the analysis settings, the user must click the blue PLAY icon in the upper-left corner to run the analysis. The results will be generated in ".txt" and/or ".xlsx" formats.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cbcb2e98-08db-4833-8458-e3d98d1228cf" alt="Image">
</p>

<p align="justify">
The output file in ".txt" format contains various pieces of information, especially highlighting the tests for fixed and/or random effects. Below is the initial section of this file.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/79f33baa-5b2a-49d5-a906-56e8f72fd1a4" alt="Image">
</p>

<p align="justify">
The results of the fixed and random effects tests are presented below:
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/0a19bf7e-f53e-46e5-8943-684abdcbd989" alt="Image">
</p>

<p align="justify">
The individual analysis showed a significant effect of treatments (ID), years, and the interaction between treatments and years. The results file also provides the experiment mean (1074.9358) and the average standard deviation of contrasts between pairs of treatments (ID) (8.5046).
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/50143b28-5f38-4345-9aa4-a9c5ae943465" alt="Image">
</p>

---
