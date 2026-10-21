---
layout: default
title: Data Science Portfolio
---

# Li Hongda

## Data Science Portfolio

I am a data science student interested in turning messy questions into clear, reproducible analyses. My work focuses on exploratory data analysis, careful data cleaning, statistical reasoning, and communicating findings through accessible visualizations.

> **Featured project at a glance:** Penguin species can be classified from four body measurements with 97.1% leave-one-out accuracy. The main limitation is that the result comes from one dataset and has not been validated on an independent population.

[View my project repository](https://github.com/Treinta666/data-science-project){: .btn .btn--primary}

## Technical skills

- **Programming:** Python, SQL (learning), Git, GitHub
- **Data analysis:** pandas, NumPy, exploratory data analysis, data cleaning
- **Visualization:** Matplotlib, accessible chart design
- **Machine learning:** feature standardisation, nearest-centroid classification, leave-one-out validation
- **Communication:** technical writing, README documentation, reproducible workflows

## Featured project

### Can penguin measurements identify a species?

**Research question:** How do bill, flipper, and body-mass measurements differ among Adelie, Chinstrap, and Gentoo penguins, and how accurately can these four measurements classify a penguin's species?

**Project status:** Completed

![Scatter plot of bill length and bill depth, coloured by penguin species.]({{ '/assets/images/bill_scatter.png' | relative_url }})

*Figure: Bill length and bill depth by species. The large X marks show species centroids.*

The visualization shows that Gentoo penguins have relatively shallow bills and a distinct morphological profile. Chinstrap penguins tend to have long but shallow bills, while Adelie penguins have shorter and deeper bills. Adelie and Chinstrap overlap more, suggesting that these two species are harder to distinguish using bill measurements alone.

I used four measurements and a leave-one-out nearest-centroid classifier. The model reached **97.1% accuracy** on 342 complete cases. All Gentoo penguins were classified correctly; the ten errors were split evenly between Adelie and Chinstrap. The main limitation is that the model was evaluated on one public dataset from the Palmer Archipelago, so its accuracy may not transfer to other populations.

[Read the code and full documentation](https://github.com/Treinta666/data-science-project)

## What this project demonstrates

- A complete workflow from a research question to a validated result
- Transparent handling of missing values and model evaluation
- Reproducible code with a documented dataset and requirements file
- Clear communication of findings, uncertainty, and limitations
- Respect for data licensing and privacy

## Reproducibility

The repository includes the Python analysis script, the public-domain dataset, a requirements file, generated result tables, and instructions for creating a virtual environment and running the analysis.


