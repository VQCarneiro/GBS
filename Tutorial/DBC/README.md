---

![Image](https://github.com/user-attachments/assets/762d2f59-8eb0-40eb-913f-c98ffc2f9c34)

---

🌎 Language:
- 🇧🇷 [Português](README_pt-BR.md)

---

- GBS is a free software designed to perform statistical analyses applied to quantitative genetics and plant breeding.  
- Below, we present the user manual and a case study of one of the data analysis procedures available in the GBS software.

---

## Individual Analysis of Experiments

---

### Randomized Complete Block Design (RCBD)

---

- For demonstration purposes, an example involving the evaluation of 30 treatments of a plant species for the trait “100-grain weight” was used.

---

<p align="justify">
The figure below shows where the procedure for individual analysis under a randomized complete block design can be accessed in the software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/28610e15-a01c-4417-9865-7ff6c05ec220" alt="Image">
</p>

<p align="justify">
The first step is to create a spreadsheet in a ".csv" file format. This file must contain, at minimum, the following columns in the specified order: Replication and Treatments. Additional columns correspond to the evaluated traits, and the dataset may include one or more traits. The figure below illustrates the analysis procedure using the example dataset provided in the software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/4c8fe6fb-d5f7-4a80-b8d8-fb1ac2b8eec0" alt="Image">
</p>

<p align="justify">
After loading the dataset, the user must navigate to the procedures tab and define the nature of the effects in the statistical model. If the treatment effect is considered fixed, the user may also select a multiple comparison test to be performed alongside the individual analysis.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/67ed1667-5449-4ce9-83aa-c1c4934a30d9" alt="Image">
</p>

<p align="justify">
Once the analysis settings are defined, the user should click the blue PLAY icon located in the upper-left corner of the interface to run the analysis. The results will be generated in ".txt" and/or ".xlsx" formats.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c708a766-dbc8-4189-be38-2d23b1255be2" alt="Image">
</p>

<p align="justify">
The output file in ".txt" format contains several pieces of information, with particular emphasis on hypothesis tests for fixed and/or random effects. The initial section of this output file is illustrated below.
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
The individual analysis revealed a significant treatment effect for the trait M100G. It was observed that 97.07% of the total variation was attributed to treatment effects. The output file also provides the overall mean of the experiment (28.7301 g), coefficient of variation (3.4161%), and the average standard deviation of treatment variances (0.8085).
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a2017004-1780-4172-8e82-040aaf36533b" alt="Image">
</p>
