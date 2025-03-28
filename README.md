\documentclass[12pt]{article}
\usepackage[margin=1in]{geometry}
\usepackage{hyperref}
\usepackage{graphicx}

\title{README - Spatial Data and Mapping Exam}
\author{Anahí Reyes Miguel}
\date{\today}

\begin{document}

\maketitle

\section*{📍 Overview}

This project aims to analyze spatial data from San Francisco using R. The focus is on neighborhood boundaries, cultural districts, demographic attributes, and business distributions. The analysis includes geospatial joins, data visualization, and exploratory spatial analysis using \texttt{sf}, \texttt{ggplot2}, and \texttt{dplyr} packages.

\section*{📂 Folder Structure}

\begin{verbatim}
├── Spatial data and mapping.Rmd   # Main analysis script
├── data/
│   ├── sfnh.geojson               # Neighborhood boundaries
│   ├── cultural_district.geojson # Cultural districts
│   ├── sfnh_dem.csv              # Demographic attributes
│   ├── sfbiz_by_type.csv         # Business data
\end{verbatim}

\section*{🧰 Dependencies}

The following R packages are required to run this project:

\begin{itemize}
  \item \texttt{sf}
  \item \texttt{ggplot2}
  \item \texttt{dplyr}
  \item \texttt{here}
  \item \texttt{tibble}
  \item \texttt{tidyr}
  \item \texttt{knitr}
\end{itemize}

You can install them with:

\begin{verbatim}
install.packages(c("sf", "ggplot2", "dplyr", "here", "tibble", "tidyr", "knitr"))
\end{verbatim}

\section*{📊 Data Sources}

The datasets include:
\begin{itemize}
  \item San Francisco neighborhood polygons
  \item Cultural district boundaries
  \item Demographic data by neighborhood
  \item Types and locations of businesses
\end{itemize}

All datasets are located in the \texttt{/data} folder.

\section*{▶️ How to Run}

\begin{enumerate}
  \item Open \texttt{Spatial data and mapping.Rmd} in RStudio.
  \item Use the \texttt{Knit} button to render the PDF, or run the chunks manually.
  \item Ensure all data files are correctly placed in the \texttt{data} directory.
\end{enumerate}

\textbf{Note:} To export to PDF, you need a \LaTeX{} distribution installed (e.g., \texttt{TinyTeX} or \texttt{TeX Live}).

\section*{📌 Author}

Anahí Reyes Miguel \\
\texttt{anahi.reyes-miguel@polytechnique.edu}

\end{document}