---

![Image](https://github.com/user-attachments/assets/762d2f59-8eb0-40eb-913f-c98ffc2f9c34)

---

🌎 Language:
- 🇧🇷 [Portuguese](README_pt-BR.md)

---

- GBS is a free software designed for performing statistical analyses applied to quantitative genetics and plant breeding.
- Below we present the manual and a case study of one of the data analysis procedures performed in the GBS software.

---

## Joint Analysis of Experiments

---

### Completely Randomized Design

---

- For demonstration purposes, the evaluation of 9 treatments of a plant species in two experiments regarding total dry mass (TDM) was used.

---

<p align="justify">
The figure below shows where the joint analysis procedure for experiments in a completely randomized design is located in the software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b2e0f0ed-6fe8-4dec-9581-f8070f704e0a" alt="Image">
</p>

<p align="justify">
The first step consists of creating a spreadsheet in ".csv" format. This spreadsheet must contain the identification of experiments in the first column (Exp) and treatments (Treat) in the second column. The remaining columns correspond to the evaluated traits, and there may be one or more. The figure below presents the analysis procedure using the software's example file.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/6abbb264-db41-4465-b4c2-7de02d7ea5c2" alt="Image">
</p>

<p align="justify">
After loading the file, the user must access the procedures tab and define the nature of the effects in the statistical model. In the procedures tab, it is also possible to define whether the analysis will consider residual and block variances as homogeneous or heterogeneous. Additionally, if the treatment effect is considered fixed, it is possible to select a mean comparison test (Means tab) to be performed along with the analysis.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/316fa090-bd9c-40f9-873f-531d98558ba7" alt="Image">
</p>

<p align="justify">
After defining the analysis settings, the user must click the blue PLAY icon in the upper left corner to run the analysis. The results will be generated in ".txt" and/or ".xlsx" formats.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c7a6815e-069c-4804-989b-d60090b065a9" alt="Image">
</p>

<p align="justify">
The output file in ".txt" format contains several pieces of information, with emphasis on fixed and/or random effects tests. The initial part of this file is shown below.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/535f7702-d5d0-4768-ab9d-6ab6534e3186"  alt="Image">
</p>

<p align="justify">
The results of the fixed and random effects tests are presented below:
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/4f507754-f585-4ff8-9b97-fc62020733c9" alt="Image">
</p>

<p align="justify">
The individual analysis showed a non-significant treatment effect for the TDM trait. The results file also presents the experiment mean (43.5907) and the mean standard deviation of variances among treatments (3.6587).
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/3863aad1-d91d-45f1-84e7-1f83c6fda328" alt="Image">
</p>
