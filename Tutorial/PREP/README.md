---

![Image](https://github.com/user-attachments/assets/762d2f59-8eb0-40eb-913f-c98ffc2f9c34)

---

🌎 Language:
- 🇧🇷 [Português](README_pt-BR.md)

---

- GBS is a free software designed to perform statistical analyses applied to quantitative genetics and plant breeding.
- Below, we present the manual and a case study of one of the data analysis procedures performed using the GBS software.

---

## Individual Analysis of Experiments

---

### Partially Replicated Design

---

- For demonstration purposes, the evaluation of 307 treatments of a plant species was used, considering specific gravity (SG).

---

<p align="justify">
The figure below shows where the procedure for individual analysis of experiments using a partially replicated design is located within the software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a0faeb35-ca3f-45b3-9d94-1700bf56f2e0" alt="Image">
</p>

<p align="justify">
The first step is to create a spreadsheet in ".csv" format. This file must contain, in the first column, the row identification (Row), in the second column the column identification (Column), and in the third column the treatment identification (ID). The remaining columns correspond to the evaluated traits, and there may be one or more. The figure below illustrates the analysis procedure using the example file provided by the software. In this tab, you can select which variable you want to analyze.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ab5e1152-9db0-4d92-ac26-85ce3bf0294d" alt="Image">
</p>

<p align="justify">
After loading the file, the user must access the procedures tab and define the nature of the effects in the statistical model. If the treatment effect is considered fixed, it is possible to select a mean comparison test to be performed along with the analysis.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ffac9103-161c-430b-8172-7d5aad1dcff5" alt="Image">
</p>

<p align="justify">
After defining the analysis settings, the user must click the blue PLAY icon in the upper left corner to execute the analysis. The results will be generated in ".txt" and/or ".xlsx" formats.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ad88f8c4-fe9c-4b4b-929e-8c1d9828b648" alt="Image">
</p>

<p align="justify">
The output file in ".txt" format contains various pieces of information, with emphasis on the tests for fixed and/or random effects. The initial part of this file is presented below.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cbb6fe12-5b02-4f30-ac83-9f0e4d420e4f" alt="Image">
</p>

<p align="justify">
The results of the tests for fixed and random effects are shown below:
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/bd767844-f833-4d0e-8767-f3f15f01bd8e" alt="Image">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c7de40d8-cef7-455f-a93c-bf7d65e4eb90" alt="Image">
</p>

<p align="justify">
The individual analysis revealed a significant treatment effect for the evaluated trait. The results file also provides the experimental mean (1068.8455), the coefficient of variation (0.9034%), and the average standard deviation of variances among treatments (13.2633).
</p>
