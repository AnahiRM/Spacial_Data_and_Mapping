# 📍 Spatial Data and Mapping Exam

**Author**: Anahí Reyes Miguel  
**Email**: anahi.reyes-miguel@polytechnique.edu  
**Date**: March 2025

## 📝 Overview

This project analyzes spatial data from San Francisco using R. It focuses on visualizing and combining data related to:

- Neighborhood boundaries
- Cultural districts
- Demographic indicators
- Business types

The goal is to explore spatial relationships and trends using geographic data and geovisualization tools.

## 📁 Folder Structure

## 📁 Folder Structure

| Path                                | Description                                       |
|-------------------------------------|---------------------------------------------------|
| `.Rhistory`                         | R session history (optional)                     |
| `.Rproj.user/`                      | R project metadata                               |
| `.git/`                             | Git version control directory                    |
| `.gitignore`                        | Specifies intentionally untracked files to ignore|
| `LICENSE`                           | Project license                                  |
| `README.md`                         | Project overview and usage instructions          |
| `Spatial data and mapping.Rmd`      | Main analysis script (R Markdown)                |
| `Spatial data and mapping.Rproj`    | R project configuration file                     |
| `Spatial-data-and-mapping.pdf`      | Rendered PDF output from R Markdown              |
| `data/`                             | Raw data folder                                  |
| ├── `cultural_district.geojson`     | Cultural districts shapefile                     |
| ├── `sfnh.geojson`                  | Neighborhood boundaries                          |
| └── `sfnh_dem.csv`                  | Demographic data by neighborhood                 |
| `processed-data/`                   | Processed and cleaned data                       |
| └── `sfbiz_by_type.csv`             | Business distribution by type                    |
| `output/`                           | Visualizations and mapping results               |
| ├── `class_map.png`                 | Map showing business class clusters              |
| ├── `combined_plot.png`            | Combined visualization of selected variables     |
| ├── `map_racial_typology.png`      | Map showing racial typology by neighborhood      |
| └── `prop_map.png`                  | Map showing proportion of selected demographic   |

## 📦 Dependencies

This project uses the following R packages:

- `sf`
- `ggplot2`
- `dplyr`
- `here`
- `tibble`
- `tidyr`
- `knitr`

You can install them with:

```r
install.packages(c("sf", "ggplot2", "dplyr", "here", "tibble", "tidyr", "knitr"))

🚀 How to Run
	1.	Clone the repository and open the project in RStudio.
	2.	Open Spatial data and mapping.Rmd.
	3.	Knit to PDF or run each chunk interactively.
	4.	Make sure all datasets are stored in a folder called /data.

🧠 Notes
	•	The script uses here::here() to manage file paths.
	•	To knit to PDF, you will need a LaTeX distribution such as TinyTeX.
	•	All maps and visualizations are generated using ggplot2 and sf.

📬 Contact

If you have any questions, feel free to contact me at:
📧 anahi.reyes-miguel@polytechnique.edu

