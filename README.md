📊 **Interactive Data Visualisation in R with ggplotly**

This repository contains a R tutorial that demonstrates how to make your R visualisations interactive using {ggplot2} + {plotly}.
It is structured as a workshop with case studies, exercises, and solutions.

📂 **Contents**

- ggplotly_tutorial.qmd – the main Quarto file (open in RStudio or VS Code).
- simulated_health_data.csv – simulated health dataset for Case Study 1.
- simulated_covid_strains.csv – simulated COVID dataset for Case Study 2.
- simulated_malaria_gwas.csv – simulated malaria genomics dataset for Case Study 3.
- README.md – this file.

🚀 **Getting Started**

_**1. Clone the repository**_

  git clone https://github.com/KirstyMcCann/2025-Sep-18_Rladies_ggplotly_workshop.git

  cd 2025-Sep-18_Rladies_ggplotly_workshop

_**2. Open in RStudio**_

  Open workshop_tutorial.rmd

_**3. Or clone github repo in Google Collabs**_

- Open Colab
  Go to [Google Colab](https://colab.google/).

- Open the workshop notebook from GitHub
  Click File → Open notebook.

- Select the GitHub tab.
  Enter:
    KirstyMcCann/2025-Sep-18_Rladies_ggplotly_workshop
    Choose the .ipynb file from the list.

- Save your own copy
  Go to File → Save a copy in Drive.
  This makes an editable version in your Google Drive.

- Install required packages Run the setup cell in the notebook (this installs R packages if needed).

- Download workshop files (data)
  In the first code cell, clone the repository:
    system("git clone https://github.com/KirstyMcCann/2025-Sep-18_Rladies_ggplotly_workshop.git")
    setwd("2025-Sep-18_Rladies_ggplotly_workshop")

- Run the notebook
  Use Runtime → Run all to execute all code cells in order.

**📖 Case Studies**

_Health Data_ – How does age and lifestyle (smoking, exercise) influence blood pressure across regions?

- Scatterplots, multivariate plots, boxplots, correlation heatmaps.

- Exercises include faceting, adding regression lines, and exploring interactions.

_COVID-19 Strains_ – How do strains spread across countries and time?

- Interactive maps, time series, phylogenetic trees.

- Exercises include changing projections, faceting by country, and zooming into time periods.

_Malaria Genomics_ – How is drug resistance spreading in parasite populations?

- Interactive PCA, GWAS Manhattan plot, logistic regression, temporal trends.

- Exercises include highlighting resistance SNPs, faceting by region, and filtering time windows.

Each case study contains:

- 🖼️ Interactive plots

- 💡 Exercises in callout boxes

- ✅ Hidden solutions (expandable)

- 📝 Reflection prompts


🙌 **Credits**

Developed and maintained by Kirsty McCann for teaching interactive data visualisation in R.

🎉 **Have fun with ggplotly!** 🎉
