------------------------------------------------------------------------

![Image](https://github.com/user-attachments/assets/762d2f59-8eb0-40eb-913f-c98ffc2f9c34)

------------------------------------------------------------------------

🌎 Language: - 🇧🇷 [Português](README_pt-BR.md)

------------------------------------------------------------------------

-   GBS is a free software designed for performing statistical analyses
    applied to quantitative genetics and plant breeding.
-   Below, we present a user guide and a case study of one of the data
    analysis procedures performed using the GBS software.

------------------------------------------------------------------------

## Individual Experiment Analyses

------------------------------------------------------------------------

### Augmented Block Design

------------------------------------------------------------------------

-   For demonstration purposes, the evaluation of 493 treatments of a
    plant species for specific gravity (SG) was used.

------------------------------------------------------------------------

The figure below shows where the procedure for individual analysis of
experiments using an augmented block design is located within the
software.

![Image](https://github.com/user-attachments/assets/d861b898-7404-45aa-8621-ca39feefab6f)

------------------------------------------------------------------------

The first step consists of preparing a spreadsheet in ".csv" format.
This file must contain, obligatorily, block identification in the first
column and treatment identification in the second column. The remaining
columns correspond to the evaluated traits, and there may be one or
more. The figure below illustrates the analysis procedure using the
example file provided with the software.

![Image](https://github.com/user-attachments/assets/2aa46b18-8789-477d-9d87-20a68d184537)

------------------------------------------------------------------------

After loading the file, the user must access the procedures tab and
define the nature of the effects in the statistical model. If the
treatment effect is considered fixed, it is possible to select a mean
comparison test to be performed along with the analysis.

![Image](https://github.com/user-attachments/assets/5e29d069-062a-4ee6-a5cc-ffc3c131fb2d)

------------------------------------------------------------------------

After defining the analysis settings, the user must click the blue PLAY
icon in the upper-left corner to execute the analysis. The results will
be generated in ".txt" and/or ".xlsx" formats.

![Image](https://github.com/user-attachments/assets/6cea531f-63f8-48ff-9014-167e23417a85)

------------------------------------------------------------------------

The output file in ".txt" format contains various pieces of information,
with emphasis on fixed and/or random effects tests. The initial section
of this file is shown below.

![Image](https://github.com/user-attachments/assets/2f2582f8-262d-446c-8088-73726ef51bb3)

------------------------------------------------------------------------

The results of fixed and random effects tests are presented below:

![Image](https://github.com/user-attachments/assets/65f19297-774e-40a9-b62e-54b06bcc83fa)

------------------------------------------------------------------------

The individual analysis revealed a significant treatment effect for the
SG trait. The results file also provides the experiment mean
(1067.3823), the coefficient of variation (0.5389%), and the average
standard deviation of variances among treatments (9.8463).

![Image](https://github.com/user-attachments/assets/a6887218-741b-48af-8ddf-09f303ea0a18)
