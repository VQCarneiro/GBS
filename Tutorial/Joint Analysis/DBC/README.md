---

![Image](https://github.com/user-attachments/assets/762d2f59-8eb0-40eb-913f-c98ffc2f9c34)

---

🌎 Language:
- 🇺🇸 [Portuguese](README_pt-Br.md)
  
---

- GBS is a free software designed for performing statistical analyses applied to quantitative genetics and plant breeding.
- Below, we present a manual and a case study of one of the data analysis procedures carried out in the GBS software.

---

## Joint Analysis of Experiments

---

### Completely Randomized Block Design

---

- For demonstration purposes, the evaluation of 29 treatments of a plant species in two experiments was used, considering the mass of 100 grains (M100G).

---

<p align="justify">
The figure below shows where the joint analysis procedure for experiments in a completely randomized block design is located within the software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/68888a5a-b0f6-4c64-a827-ea697dc4610a"  alt="Image">
</p>

<p align="justify">
The first step consists of creating a spreadsheet in ".csv" format. This file must contain the identification of experiments in the first column (Amb), repetitions (REP) in the second column, and Treatments (Trat) in the third column. The remaining columns correspond to the evaluated traits, and there may be one or more. The figure below presents the analysis procedure using the example file provided in the software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/1b00e7b1-60b4-4a2c-ba18-b3f5554c73c3" alt="Image">
</p>

<p align="justify">
After loading the file, the user must access the procedures tab and define the nature of the effects in the statistical model. In this tab, it is also possible to define whether the analysis will consider residual and block variances as homogeneous or heterogeneous. Additionally, if the treatment effect is considered fixed, it is possible to select a mean comparison test (Means tab) to be performed along with the analysis.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/558faaa9-87cb-445d-82c7-eeb136c93a1b" alt="Image">
</p>

<p align="justify">
After defining the analysis settings, the user must click the blue PLAY icon in the upper-left corner to run the analysis. The results will be generated in ".txt" and/or ".xlsx" formats.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/fc1570ef-4276-47cf-bc57-7e9cf738de86" alt="Image">
</p>

<p align="justify">
The output file in ".txt" format contains various information, with emphasis on fixed and/or random effects tests. The initial part of this file is shown below.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/09242d6b-fce1-4651-af39-62fed93cbe72"  alt="Image">
</p>

<p align="justify">
The results of fixed and random effects tests are presented below:
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/31a0da96-0939-4b6b-9d22-d729c1dd2737" alt="Image">
</p>

<p align="justify">
The individual analysis allowed observing a significant effect of treatments, environments, and treatment × environment interaction for the M100G trait. The results file also presents the experiment mean (27.3064) and the average standard deviation of variances among treatments (0.8424).
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/427271b0-8260-4b46-b579-205d9b383e8d" alt="Image">
</p>

---
