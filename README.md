# Sus-Din-Out
This GitHub repository contains Jupyter Notebooks detailing our methods for analyzing sustainable dining practices in Tokyo.

#Contents
1. Notebooks
Main Analytical Notebooks
SDOI_calculation.ipynb: Calculates the Sustainable Dining Out Index (SDOI) across railway stations, lines, and administrative districts in Tokyo.
Includes station-level, line-level, and district-level analyses, enabling comprehensive comparisons of sustainability disparities.

Menu_data_analysis.ipynb: Newly added for this release, this notebook analyzes an expanded dataset of recipes and menu items, enabling deeper insights into nutrition, pricing, and diversity in restaurant offerings.

Monte_Carlo_analysis.ipynb: Introduced to ensure the robustness of results, this notebook implements Monte Carlo simulations to incorporate variability into our analysis. It refines the computation of nutritional indices and incorporates uncertainty into key findings.

Price_considered.ipynb: Explores economic pathways to sustainable dining by examining affordability and pricing metrics in the context of diverse dining environments.

Optimization and Visualization
Results_analysis.ipynb:Visualizes disparities in restaurant distribution and sustainability across Tokyo's urban areas, providing spatial context to the analysis.

Visulization_of_optimization.ipynb: Newly added, this notebook visualizes the results of our optimization models. It highlights key recommendations for improving sustainable dining access across underperforming areas.

2. Study Context
This repository supports our research on the interplay between urbanization, culinary identity, and sustainability in dining choices. It provides an analytical framework for assessing disparities in sustainable dining options and identifying strategies for improvement. The methods are grounded in data-driven analyses, incorporating dimensions like pricing, nutrition, and environmental impact, as well as leveraging optimization modeling to propose actionable solutions.

3. File Structure
Sus-Din-Out/
│
├── Menu_data_analysis.ipynb          # New notebook for analyzing expanded recipe dataset.
├── SDOI_calculation.ipynb            # Calculates SDOI at various spatial levels.
├── Monte_Carlo_analysis.ipynb        # Introduces variability and robustness checks.
├── Price_considered.ipynb            # Explores economic pathways to sustainable dining.
├── Results_analysis.ipynb            # Visualizes disparities in restaurant distribution.
├── Visulization_of_optimization.ipynb # New notebook for optimization model visualization.
├── data/                             # Folder containing raw and processed datasets.
├── figures/                          # Folder for generated visualizations and plots.
├── requirements.txt                  # List of required Python libraries.
└── README.md                         # This file.

4. License
This repository is licensed under the MIT License. See LICENSE for details.
