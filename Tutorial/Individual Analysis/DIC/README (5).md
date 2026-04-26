---

![Image](https://github.com/user-attachments/assets/762d2f59-8eb0-40eb-913f-c98ffc2f9c34)

---

🌎 Language:
- 🇧🇷 [Portuguese](README_pt-BR.md)

---

- GBS is a free software designed to perform statistical analyses applied to quantitative genetics and plant breeding.
- Below, we present the manual and a case study of one of the data analysis procedures carried out in the GBS software.

---

## Individual Analyses of Experiments

---

### Completely Randomized Design

---

- For demonstration purposes, the evaluation of 9 treatments of a plant species regarding total dry mass was used.

---

<p align="justify">
The figure below shows where the individual experiment analysis procedure in a completely randomized design is located within the software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/bdd54d8c-800d-4920-af12-880056d720a2" alt="Image">
</p>

<p align="justify">
The first step consists of creating a spreadsheet in ".csv" format. This spreadsheet must contain the Treatments in the first column. The remaining columns correspond to the evaluated traits, and there may be one or more. The figure below shows the analysis procedure using the example file provided by the software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/4033571b-fa59-402f-b229-c0fdc7c5fa95" alt="Image">
</p>

<p align="justify">
After loading the file, the user must access the procedures tab and define the nature of the effects in the statistical model. If the treatment effect is considered fixed, it is possible to select a mean comparison test to be performed along with the analysis.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/f75e282b-8bd0-4aa2-8f8d-d1d4cd8fe9ba" alt="Image">
</p>

<p align="justify">
After defining the analysis settings, the user must click the blue PLAY icon in the upper-left corner to run the analysis. The results will be generated in ".txt" and/or ".xlsx" formats.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/1d284c6a-e39e-4ebf-8e5b-53259e2096f6" alt="Image">
</p>

<p align="justify">
The output file in ".txt" format contains various pieces of information, with emphasis on fixed and/or random effects tests. The initial part of this file is shown below.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/61f4588c-b17a-4399-bfcd-0102aefc49ac" alt="Image">
</p>

<p align="justify">
The results of the fixed and random effects tests are presented below:
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/57c7867d-a252-4b33-9234-37a401bcdb17" alt="Image">
</p>

<p align="justify">
The individual analysis showed a non-significant treatment effect for the MST trait. The results file also presents the experiment mean (38.3925), the coefficient of variation (14.8683%), and the average standard deviation of variances among treatments (4.0364).
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/9d9b806c-6f06-49ab-b86c-cff822645d43" alt="Image">
</p>
