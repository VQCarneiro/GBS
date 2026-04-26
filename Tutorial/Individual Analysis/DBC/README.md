---

![Image](https://github.com/user-attachments/assets/762d2f59-8eb0-40eb-913f-c98ffc2f9c34)

---

🌎 Language:
- 🇧🇷 [Português](README_pt-BR.md)

---

- GBS is a free software designed for performing statistical analyses applied to quantitative genetics and plant breeding.
- Below, we present the manual and a case study of one of the data analysis procedures carried out in the GBS software.

---

## Individual Analyses of Experiments

---

### Randomized Complete Block Design

---

- For demonstration purposes, the evaluation of 30 treatments of a plant species for the mass of 100 grains was used.

---

<p align="justify">
The figure below shows where the procedure for individual analysis of experiments in a randomized complete block design is located in the software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/28610e15-a01c-4417-9865-7ff6c05ec220" alt="Image">
</p>

<p align="justify">
The first step consists of creating a spreadsheet in ".csv" format. This spreadsheet must necessarily contain the columns Replication and Treatments, in this order. The remaining columns correspond to the evaluated traits, and there may be one or more. The following figure presents the analysis procedure using the software's example file.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/4c8fe6fb-d5f7-4a80-b8d8-fb1ac2b8eec0" alt="Image">
</p>

<p align="justify">
After loading the file, the user must access the procedures tab and define the nature of the effects in the statistical model. If the treatment effect is considered fixed, it is possible to select a mean comparison test to be performed along with the analysis.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/67ed1667-5449-4ce9-83aa-c1c4934a30d9" alt="Image">
</p>

<p align="justify">
After defining the analysis settings, the user must click the blue PLAY icon in the upper left corner to run the analysis. The results will be generated in ".txt" and/or ".xlsx" formats.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c708a766-dbc8-4189-be38-2d23b1255be2" alt="Image">
</p>

<p align="justify">
The output file in ".txt" format contains various pieces of information, with emphasis on tests of fixed and/or random effects. Below is the initial part of this file.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/efc46175-6e48-4d55-98d9-bfc733308197" alt="Image">
</p>

<p align="justify">
The results of the fixed and random effects tests are presented below:
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/40cfcea2-03e5-42c1-b741-74982c61347e" alt="Image">
</p>

<p align="justify">
The individual analysis allowed observing a significant treatment effect for the trait M100G. It was verified that 97.07% of the total variation was attributed to the treatment effect. The results file also presents the experiment mean (28.7301 g), the coefficient of variation (3.4161%), and the average standard deviation of variances among treatments (0.8085).
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a2017004-1780-4172-8e82-040aaf36533b" alt="Image">
</p>
