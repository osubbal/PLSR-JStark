# About

- Coding Language: [R]
- Version: [3.6.1]
- Required Packages: 
	- [library(corrplot)]
	- [library(tidyverse)]
	- [library(PTCA4CATA)]
	- [library(data4PCCAR)] # PLSR 
	- [library(boot)]
	- [library(dplyr)]
	- [library(ExPosition)]

- Related Publication: [Stark, J., Hiersche, K. J., Yu, J. C., Hasselbach, A. N., Abdi, H., Hayes, S. M., & Alzheimer’s Disease Neuroimaging Initiative (2023). Partial Least Squares Regression Analysis of Alzheimer's Disease Biomarkers, Modifiable Health Variables, and Cognitive Change in Older Adults with Mild Cognitive Impairment. Journal of Alzheimer's disease : JAD, 93(2), 633–651. https://doi.org/10.3233/JAD-221084]

# Usage

Goal: Run a PLS regression analysis and graphs for visualization.
Original Usage: [all data obtained from ADNI]
  Predictor variables = modifiable health variables, AD biomarkers, and demographics
  Outputs = composite scores of episodic memory and executive function 

How to Use: 
- to run this code, you will need two cleaned datasheets that do not have subject IDs in them: 
  1. predictor variables
  2. outcome variables

# Further Reading
- A76. Abdi, H. (2010). Partial least square regression, projection on latent structure regression, PLS-Regression. Wiley Interdisciplinary Reviews: Computational Statistics, 2, 97-106.

- A114. Beaton, D., Dunlop, J., ADNI, & Abdi, H. (2016). Partial Least Squares-Correspondence Analysis: A framework to simultaneously analyze behavioral and genetic data. Psychological Methods, 21, 621-651.

- C75. Abdi, H., & Williams, L.J. (2013). Partial least squares methods: Partial least squares correlation and partial least square regression. In: B. Reisfeld & A. Mayeno (Eds.), Methods in Molecular Biology: Computational Toxicology. New York: Springer Verlag. pp. 549-579.

- C37. Abdi, H. (2007). Partial least square regression (PLS regression). In N.J. Salkind (Ed.): Encyclopedia of Measurement and Statistics. Thousand Oaks (CA): Sage. pp. 740-744.
