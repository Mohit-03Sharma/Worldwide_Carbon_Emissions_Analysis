# Worldwide Carbon Emissions Analysis 

> Data analytics and machine learning project exploring city-level greenhouse gas emissions (2019–2023) with geospatial mapping and predictive forecasting

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Plotly](https://img.shields.io/badge/Plotly-Geospatial-00D4FF.svg)](https://plotly.com/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange.svg)](https://scikit-learn.org/)

Comprehensive analysis of city-level emissions data identifying trends aligned with **Net Zero targets** and **UN SDGs 11 & 13**. Features interactive geospatial visualizations and baseline forecasting models.

---

## Project Highlights

- **Multi-year analysis** — Cleaned and analyzed emissions data spanning 2019–2023
- **Interactive geospatial mapping** — Choropleth visualizations comparing regions and cities
- **Trend identification** — Surfaced high-emitting hotspots and temporal patterns
- **Predictive modeling** — Baseline forecasting model for emissions trajectories
- **Sustainability alignment** — Insights connected to Net Zero goals and UN SDGs 11 & 13

---

## Notebooks Overview

Explore the analysis in this recommended order:

### 1. Core Analysis & Visualizations
**`notebooks/01_central_idea_visualisations.ipynb`**
- Exploratory data analysis
- Year-over-year emissions trends
- City/country comparisons
- Top emitters identification

### 2. Geospatial Mapping
**`notebooks/02_choropleth_visualization.ipynb`**
- Interactive choropleth maps
- Geographic pattern analysis
- Regional emission distributions

### 3. Predictive Modeling
**`notebooks/03_prediction_model.ipynb`**
- Baseline forecasting model
- Model training and evaluation
- Future emissions projections

---

## Key Outputs

- **Temporal analysis** — Year-over-year emissions movement and trends
- **Comparative insights** — City and country-level comparisons
- **Geographic patterns** — Choropleth maps revealing spatial distributions
- **Forecasts** — Predicted emission trajectories with model metrics

### Sample Visualizations

```markdown
![Emissions Trends](reports/figures/emissions_trends.png)
![Choropleth Map](reports/figures/choropleth_map.png)
![Model Predictions](reports/figures/predictions.png)
```


## Dataset

City-level greenhouse gas emissions data covering **2019–2023**.

**Setup instructions:**
1. Obtain the dataset (if not included in repository)
2. Place raw files in `data/raw/`
3. Processed/cleaned data will be saved to `data/processed/`
4. Update notebook paths if needed

> Dataset source information should be added here when available

---

## Quick Start

### Prerequisites
- Python 3.x
- Jupyter Notebook

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Mohit-03Sharma/Worldwide_Carbon_Emissions_Analysis.git
cd Worldwide_Carbon_Emissions_Analysis
```

2. **Create virtual environment and install dependencies**
```bash
python -m venv .venv

# Windows:
.venv\Scripts\activate

# macOS/Linux:
source .venv/bin/activate

pip install -r requirements.txt
```

3. **Launch Jupyter Notebook**
```bash
jupyter notebook
```

4. **Run notebooks in sequence**
- Start with `01_central_idea_visualisations.ipynb`
- Continue with `02_choropleth_visualization.ipynb`
- Finish with `03_prediction_model.ipynb`

---

## Tech Stack

**Core:** Python 3.x  
**Data Processing:** pandas, NumPy  
**Visualization:** Plotly, matplotlib  
**Machine Learning:** scikit-learn  
**Environment:** Jupyter Notebook

---

## Roadmap (Industry-Level Enhancements)

### Code Organization
- [ ] Refactor into modular `src/` pipeline (preprocess → train → evaluate)
- [ ] Add automated testing suite
- [ ] Implement logging and error handling

### Model Improvements
- [ ] Time-aware validation (train on years 2019-2022, validate on 2023)
- [ ] Model comparison: Linear/ElasticNet vs tree-based vs XGBoost/LightGBM
- [ ] Hyperparameter tuning with cross-validation
- [ ] Ensemble methods for improved accuracy

### Tracking & Deployment
- [ ] Experiment tracking with MLflow or metrics.json
- [ ] CI/CD pipeline for automated model training
- [ ] Interactive Streamlit dashboard with:
  - Dynamic filters (city, region, year)
  - Interactive maps
  - Real-time forecast visualization

---

## Project Context

This project demonstrates end-to-end data science capabilities including:

- **Data wrangling** — Cleaning and structuring multi-year city-level data
- **Exploratory analysis** — Uncovering patterns and trends in emissions
- **Geospatial visualization** — Communicating insights through interactive maps
- **Predictive modeling** — Building baseline forecasting models
- **Sustainability impact** — Connecting analysis to global climate goals

**Relevance to UN Sustainable Development Goals:**
- **SDG 11:** Sustainable Cities and Communities
- **SDG 13:** Climate Action

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit a pull request.

---

## Contact

**Mohit Sharma**  
GitHub: [@Mohit-03Sharma](https://github.com/Mohit-03Sharma)

---

<div align="center">
  <sub>Built with 🌍 for a sustainable future</sub>
</div>
