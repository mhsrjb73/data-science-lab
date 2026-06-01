# Sustainability Assessment of OECD Countries:
## A Multidimensional Framework for Evaluating Energy Transition, Climate Resilience, and Structural Contradictions

### Overview

This project develops a multidimensional sustainability assessment framework for OECD countries by integrating indicators related to Energy Transition, Climate Resilience, and Structural Sustainability.

Rather than relying solely on traditional composite rankings, the framework explores sustainability through multiple analytical perspectives including contradiction analysis, clustering, principal component analysis (PCA), dominance analysis, dynamic trajectories, policy scenario simulations, and efficiency frontiers.

The objective is to provide a more comprehensive understanding of sustainability performance and structural balance across countries.

---

## Research Questions

- Which OECD countries demonstrate the strongest overall sustainability performance?
- How balanced are countries across energy transition and climate resilience dimensions?
- Which countries exhibit structural contradictions despite high aggregate performance?
- Can sustainability archetypes be identified through clustering techniques?
- How do sustainability trajectories evolve over time?
- What policy interventions may improve sustainability performance and balance?

---

## Methodological Framework

### Data Processing

- Data collection from OECD and international sustainability databases
- Missing value treatment using KNN Imputation
- Min-Max normalization
- Construction of composite indicators

### Analytical Methods

1. Composite Sustainability Ranking
2. Trade-Off Analysis
3. Contradiction Index Analysis
4. Sustainability Archetypes (K-Means Clustering)
5. Principal Component Analysis (PCA)
6. Correlation Network Analysis
7. Poset-Inspired Dominance Analysis
8. Dynamic Trajectory Analysis
9. Policy Scenario Simulation
10. Sustainability Efficiency Frontier

---

## Repository Structure

```text
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── data_preparation.ipynb
│   ├── sustainability_analysis.ipynb
│   └── visualization.ipynb
│
├── figures/
│   ├── fig01_top15_ranking.png
│   ├── fig02_tradeoff_map.png
│   ├── fig03_contradiction_index.png
│   └── ...
│
├── report/
│   └── Sustainability_Assessment_Report.pdf
│
├── requirements.txt
│
└── README.md
```

---

## Key Analytical Outputs

- Composite Sustainability Rankings
- Trade-Off Maps
- Contradiction Profiles
- Sustainability Archetypes
- PCA Biplots
- Correlation Networks
- Dominance Structures
- Dynamic Sustainability Trajectories
- Policy Scenario Simulations
- Sustainability Efficiency Frontiers

---

## Main Findings

The analysis suggests that sustainability leadership cannot be understood solely through aggregate performance scores.

Several countries achieve high overall performance while simultaneously exhibiting substantial structural contradictions between energy transition and climate resilience dimensions.

The results highlight the importance of balancing sustainability dimensions rather than maximizing isolated performance indicators.

---

## Software and Libraries

- Python 3.x
- Pandas
- NumPy
- Scikit-Learn
- SciPy
- NetworkX
- Matplotlib
- Seaborn

---

## Author

Mahsa Rajabi

M.Sc. Student in Data Science  
University of Milano-Bicocca

---

## License

This repository is intended for academic and research purposes.
