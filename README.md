
# 🧬 AdaptiveTraitEvolution

Repository for analyzing trait evolution in nektonic and carnivorous species using polynomial regression, Gaussian Process Regression, Approximate Bayesian Computation, and stochastic simulations. This repository contains code and documentation for analyzing the evolution of nektonic and carnivorous species using various statistical and computational methods.
This repository provides a Kotlin-based implementation for analyzing the evolution of traits in nektonic and carnivorous species using empirical and simulated datasets. It supports advanced modeling techniques such as:

- Polynomial Regression
- Gaussian Process Regression (GPR)
- Approximate Bayesian Computation (ABC)
- Stochastic simulations (Ornstein-Uhlenbeck & Brownian motion)

## 📚 Project Scope

The empirical datasets analyzed in this study include:
- Trait data for Mediterranean nektonic species (fecundity, longevity)
- Diet and ecological range data for carnivorous species (e.g., body mass, niche breadth)

Synthetic datasets were generated for stochastic modeling components.

## Contents
- `data/`: Processed and raw ecological datasets (only simulated data included due to licensing).
- `scripts/`: Python scripts for modeling and simulations.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and visualization.
- `docs/`: Documentation on methods, model assumptions, and reproducibility steps.
  AdaptiveTraitEvolution/
├── data/                # Processed and raw ecological datasets
├── scripts/             # Python modeling/simulation scripts
├── notebooks/           # Jupyter notebooks for visualization
├── models/              # Kotlin models for regression and stochastic processes
├── tests/               # Unit tests for Kotlin models
├── docs/                # Methodological documentation
├── LICENSE              # Human-readable open-source license
├── README.md            # Project overview and setup instructions
└── build.gradle.kts     # Kotlin build configuration (Gradle Kotlin DSL)

git clone https://github.com/virtualscreenlab/AdaptiveTraitEvolution.git
cd AdaptiveTraitEvolution

# Optional: For Python-based visualizations
pip install -r notebooks/requirements.txt


## Data Sources
Empirical data were sourced from:
- [Mediterranean Nekton Traits Dataset](https://pubmed.ncbi.nlm.nih.gov/32095343/)
- [Living Shoreline Nekton Dataset](https://knb.ecoinformatics.org/view/doi%3A10.5063%2FF1H70D9H)
- [Salt Marsh Nekton Monitoring Data](https://catalog.data.gov/dataset/?_tags_limit=0&tags=nekton)
- [Neotropical Carnivores Dataset](https://github.com/LEEClab/Neotropical_Carnivores)
- [CarniDIET 1.0](https://datadryad.org/dataset/doi%253A10.5061%252Fdryad.2v6wwpzmr)
  ## 📊 Other Data Sources

### 🐟 Nektonic Species Datasets

#### 1. Mediterranean Nekton Traits Dataset
- **Description**: Contains data on 23 biological traits for 235 nektonic species in the Mediterranean Sea, focusing on life cycle, distribution, ecology, and behavior.
- **Source**: Published in Ecological Indicators and indexed in PubMed.
- **Access**: [PubMed Abstract](https://pubmed.ncbi.nlm.nih.gov/32095343/)

#### 2. Living Shoreline Nekton Dataset (North Carolina, USA)
- **Description**: A 20-year dataset documenting nekton species associated with living shorelines, harmonized for consistency.
- **Source**: Available through the Knowledge Network for Biocomplexity (KNB).
- **Access**: [KNB Dataset](https://knb.ecoinformatics.org/view/doi%3A10.5063%2FF1H70D9H)

#### 3. Salt Marsh Nekton Monitoring Data
- **Description**: Includes nekton counts used to assess densities along marsh edges and adjacent shallow non-vegetated bottoms.
- **Source**: Available via Data.gov.
- **Access**: [Data.gov Nekton Datasets](https://catalog.data.gov/dataset/?_tags_limit=0&tags=nekton)
  


#### Copyright (c) 2025 Sergey Shityakov, Muhammad Mazhar Fareed
**AdaptiveTraitEvolution: Source License**

with just a few conditions:

✅ What You Can Do:
- Use this code and data in your own research, software, or analysis.
- Modify it to suit your project needs.
- Share it with others or include it in your own repositories.
- Use it commercially (just give credit!).

📝 Please Remember To:
- Include credit to the original authors: Sergey Shityakov and research collaborator: Muhammad Mazhar Fareed.
- Mention this repository (https://github.com/virtualscreenlab/AdaptiveTraitEvolution) in any derivative work or publication.
- Clearly state any major changes you made, especially if you publish or share your own version.

🚫 What You Cannot Do:
- Hold the original authors or contributors liable for any issues or results based on this code or data.
- Use this work to mislead others about scientific findings or authorship.

🤝 In Short:
We’ve built this to advance science and support collaboration. Use it wisely and respectfully, and acknowledge the work we've done. If you improve it, we’d love to hear from you!

— The AdaptiveTraitEvolution Project Team



## Contact
For other questions, contact Sergey Shityakov: sergey.shityakov@uni-wuerzburg.de

