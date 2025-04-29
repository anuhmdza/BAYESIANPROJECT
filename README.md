# Let's create the README.md file based on the latest content requested
readme_content = """# Bayesian Project - Autism Prevalence Analysis
Author: Ana Mendoza & Marali Benitez  
Date: April 8, 2025

---

## 📚 Project Overview

This project uses Bayesian methods to estimate autism prevalence rates across multiple studies.  
We model the number of observed cases as a binomial outcome with unknown true prevalence rates (`theta`).  
We then build two models:
- A **basic Bayesian model** with individual priors for each study.
- A **hierarchical beta-binomial model** that allows studies to share information through hyperparameters (`alpha`, `beta`).

The goal is to update our beliefs about autism prevalence rates, visualize uncertainty, and assess how well the model fits the observed data.

---

## 📂 Files Included

| File | Description |
|:---|:---|
| `bayesian project.Rmd` | Main RMarkdown file that contains all code, explanations, and outputs. |
| `bayesian-project.docx` | Word document output generated from the RMarkdown file (ready to turn in). |
| `Autism Studies Dataset.csv` | The dataset used for modeling (contains sample size and number of cases for each study). |
| `bayesian-project_files/` | Folder containing supporting files generated when knitting the RMarkdown file. |
| `project.Rproj` | RStudio project file for easy project management. |

---

## 🛠 How to Run the Project

1. Open `project.Rproj` in RStudio.
2. Open the file `bayesian project.Rmd`.
3. Make sure the `Autism Studies Dataset.csv` is in the same folder.
4. Click **Knit** to generate a Word document with all the code, plots, and explanations.

> 📌 You need to have these R packages installed:
> - `rjags`
> - `coda`
> - `ggplot2`
> - `dplyr`
> - `rnaturalearth`
> - `rnaturalearthdata`

If needed, install packages with:

```r
install.packages(c("rjags", "coda", "ggplot2", "dplyr", "rnaturalearth", "rnaturalearthdata"))
