# Education Project

> Analyze ACT and SAT scores alongside Census Bureau data to establish relationships between socioeconomic factors and school performance.

---

## Project Overview

This project will determine what, if any, socioeconomic factors contribute to ACT and SAT scoring. The socioeconomic data examined incudes unemployment rates, median household income, and percentages such as students receiving free lunch and students living in a household with married parents per school zone. The ACT and SAT scores were collected from public state reporting, and is reported by school. This analysis intends to answer what the direct correlation of economic hardship is on students preparing for college, and what specific factors can be changed to improve entrance exam scores. Additionally, EDGE (Education Demographics and Geographic Estimates) provides an estimated poverty ratio for each school zone, which could further establish the link between poverty rates and exam scores.

- **Objective:** Establish relationships between socioeconomic factors and school performance
- **Domain:** Education
- **Key Techniques:** Regression, LOWESS smoothing, hexbin clustering

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** EdGap data: https://www.edgap.org/
              ACT / SAT scores: https://nces.ed.gov/ccd/pubschuniv.asp
              EDGE Poverty Estimates: https://nces.ed.gov/programs/edge/Economic/NeighborhoodPoverty
- **Description:** Excel document and CSV file containing socioeconomic data per school zone and ACT and SAT scores respectively
- **License:** 

---

## Analysis

This analysis should be run beginning to end, and does include an optional section to export and reimport the cleaned data frame. The notebook contains markdown notes of the process taken to perform these steps, and code that will provide various plots and text outputs to analyze the data files included in this repository. Some code cells include optional testing and visualizing that I produce with the assitance of an AI bot, as well as to help me understand how the code can be used to produce different outputs.

---

## Results

Socioeconomic indicators do provide meaningful explanatory evidence for average ACT scores, but data preparation and visualization shows a need for more complete data. 

---

## Authors

- Hannah Belville - [@belvilleh](https://github.com/belvilleh)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used
    pandas
    numpy
    seaborn
    matplotlib.pyplot
    scipy.stats
    plotly
    sklearn
- Tutorials or papers referenced
    N/A
- Inspiration or collaborators
    Self completed