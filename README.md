# Meta-SDoH-EpigeneticClocks
Social determinants of health and epigenetic clocks: A Systematic review and meta-analysis of 140 studies 


## Authors
- [Yayouk Willems], [Affiliation]
- [Co-author Full Name], [Affiliation]
- [Co-author Full Name], [Affiliation]

Correspondence: [your email]

---

## Associated Publication

This repository accompanies the manuscript:

**[Full citation once published]**

[Authors]. ([Year]). *[Title of paper]*. [Journal Name].  
DOI: https://doi.org/[DOI]

Status: [Published / In press / Under review at Journal Name]

---

## Project Description

This repository contains the code and summary-level data used to conduct the meta-analysis described in the manuscript above.

The repository includes:

- Scripts for data preparation  
- Scripts for performing the meta-analysis  
- Scripts for generating tables and figures  
- Supplementary material containing the meta-analysis input data  

---

## Data

The meta-analysis input data are provided in:

`supplemental_tables.xlsx`

Specifically:
- **Supplementary Table 7 (Tab 39)** contains the summary-level data used as input for the meta-analysis.
- These data are aggregated statistics.
- No individual-level participant data are included in this repository.

All summary statistics originate from previously published cohort-level analyses as cited in the manuscript.

---

## Repository Structure

```
code/
  01_prepare_data.R
  02_run_meta_analysis.R
  03_generate_tables_figures.R

data/
  supplemental_tables.xlsx

results/
  meta_outputs/
  figures/
  tables/
```

---

## Reproducibility

To reproduce the analyses:

1. Clone or download this repository.
2. Open R (version [X.X.X]).
3. Install required packages:

   - metafor
   - tidyverse
   - readxl
   - [other packages]

4. Run scripts in the following order:

```
code/01_prepare_data.R
code/02_run_meta_analysis.R
code/03_generate_tables_figures.R
```

Results will be generated in the `/results` directory.

---

## Software Environment

Analyses were conducted using:

- R version [X.X.X]
- Key packages:
  - metafor
  - dplyr
  - readxl
  - [other packages]

(Optional: paste `sessionInfo()` here for full reproducibility.)

---

## License

Code in this repository is licensed under the MIT License.

Summary-level data (Supplementary Table 7) are shared under CC-BY 4.0 unless otherwise specified.

---

## Citation

If you use this code or data, please cite:

[Full citation of your paper]

---

## Acknowledgements

[Funding sources, grants, lab name, collaborators, etc.]

