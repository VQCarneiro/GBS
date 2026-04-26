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

### Lattice Designs (Square, Rectangular, Alpha)

---

- For demonstration purposes, the evaluation of 49 treatments of a plant species was used, considering bacterial blight severity (BBS) and grain yield (YIELD).

---

<p align="justify">
The figure below shows where the procedure for individual analysis of experiments using lattice designs is located within the software. This procedure is designed to analyze data from square, rectangular, and alpha lattice experiments.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/105d8260-6240-4c65-8ebd-3f3aeb00cdc8" alt="Image">
</p>

<p align="justify">
The first step is to create a spreadsheet in ".csv" format. This file must contain, in the first column, the identification of replications (REP), in the second column the blocks, and in the third column the treatments. The remaining columns correspond to the evaluated traits, and there may be one or more. The figure below illustrates the analysis procedure using the example file provided by the software. In this tab, you can select which variable you want to analyze. In this case study, the analysis will be performed for BBS. It is important to note that analyses in the GBS software are conducted separately for each variable.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/eac07efd-f279-440b-a17d-d57f52c70f60" alt="Image">
</p>

<p align="justify">
After loading the file, the user must access the procedures tab and define the nature of the effects in the statistical model. If the treatment effect is considered fixed, it is possible to select a mean comparison test to be performed along with the analysis.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d9c43664-af8c-419c-9452-9a764c7f3f73" alt="Image">
</p>

<p align="justify">
After defining the analysis settings, the user must click the blue PLAY icon in the upper left corner to execute the analysis. The results will be generated in ".txt" and/or ".xlsx" formats.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/aa94d8d7-594f-44a2-8117-b5df45a04ae2" alt="Image">
</p>

<p align="justify">
The output file in ".txt" format contains various pieces of information, with emphasis on the tests for fixed and/or random effects. The initial part of this file is presented below.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/8a0dc53e-5893-47a0-a6a8-5071b96ee0bf" alt="Image">
</p>

<p align="justify">
The results of the tests for fixed and random effects are shown below:
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/bae4125e-2234-4c94-9b78-1c6999ed78bb" alt="Image">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/15fab0a4-eb20-4584-9bcd-738374ae2ec2" alt="Image">
</p>

<p align="justify">
The individual analysis revealed a significant treatment effect for the BBS trait. The results file also provides the experimental mean (6.6122), the coefficient of variation (16.6097%), and the average standard deviation of variances among treatments (0.8967).
</p>
