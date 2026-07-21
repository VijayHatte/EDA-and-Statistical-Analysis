# 📊 Exploratory Data Analysis & Statistical Analysis

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-013243?style=for-the-badge&logoColor=white)](https://matplotlib.org/)
[![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=white)](https://scipy.org/)

Welcome to the **EDA & Statistical Analysis** repository. This project is a comprehensive collection of structured Jupyter Notebooks designed to demonstrate and practice data wrangling, advanced data visualization, exploratory analysis, and core statistical and mathematical workflows in Python.

---

## 📂 Project Structure

```text
EDA-and-Statistical-Analysis/
├── .gitignore                  # Prevents committing checkpoint & cache files
├── README.md                   # Project documentation
├── requirements.txt            # Python library dependencies
├── data/                       # Directory for local CSV datasets (user-provided)
└── notebooks/                  # Structured topic-specific learning directories
    ├── eda/                    # Exploratory Data Analysis case studies
    ├── matplotlib/             # Plotting & visualization tutorials
    ├── pandas/                 # Data cleaning and manipulation tasks
    └── stat-math/              # Statistical methods and mathematics
```

---

## 📓 Notebook Directory & Contents

### 1. 🔍 Exploratory Data Analysis (EDA)
Case studies demonstrating end-to-end data exploration, handling real-world datasets, profiling, and finding patterns.

| Notebook | Topic / Description |
| :--- | :--- |
| 🎬 [`netflix.ipynb`](./notebooks/eda/netflix.ipynb) | Exploratory analysis of the Netflix catalog, exploring content types, ratings, release years, and country distributions. |
| 🌍 [`pollution.ipynb`](./notebooks/eda/pollution.ipynb) | Analyzing global air quality and water pollution metrics across major cities. |
| 🏃‍♂️ [`treadmill.ipynb`](./notebooks/eda/treadmill.ipynb) | Customer profiling, descriptive analytics, and demographic mapping for treadmill buyers (CardioGoodFitness). |

---

### 2. 🐼 Pandas Data Processing
Tutorials focused on importing, cleaning, merging, and reshaping data using the `pandas` library.

| Notebook | Topic / Description |
| :--- | :--- |
| 🏁 [`intro.ipynb`](./notebooks/pandas/intro.ipynb) & [`dataframe-basics.ipynb`](./notebooks/pandas/dataframe-basics.ipynb) | Foundations of Series and DataFrames, accessing columns/rows, and simple operations. |
| 🏗️ [`create-dataframe.ipynb`](./notebooks/pandas/create-dataframe.ipynb) | Initializing DataFrames from lists, dictionaries, Excel sheets, and CSVs. |
| 💾 [`read-write.ipynb`](./notebooks/pandas/read-write.ipynb) | Reading and writing CSV/Excel files, controlling headers, skipping rows, and using custom placeholders. |
| 🧼 [`handling-missing-data.ipynb`](./notebooks/pandas/handling-missing-data.ipynb) & [`replace-method.ipynb`](./notebooks/pandas/replace-method.ipynb) | Techniques for handling NaN values (`fillna`, `interpolate`, `dropna`, `replace`) and replacing custom values. |
| 🔀 [`group-by.ipynb`](./notebooks/pandas/group-by.ipynb) & [`pivot.ipynb`](./notebooks/pandas/pivot.ipynb) | Aggregating data, computing stats by groups, building pivot tables, and using cross-tabulations. |
| 🔗 [`concat.ipynb`](./notebooks/pandas/concat.ipynb) & [`merge.ipynb`](./notebooks/pandas/merge.ipynb) | Combining datasets using horizontal/vertical concatenation and database-style inner, outer, left, and right joins. |

---

### 3. 📉 Matplotlib Visualizations
Tutorials detailing the creation of clear and informative statistical plots.

| Notebook | Topic / Description |
| :--- | :--- |
| 🛠️ [`intro.ipynb`](./notebooks/matplotlib/intro.ipynb) | Understanding figures, axes, coordinate systems, and drawing basic line plots. |
| 📊 [`bar-charts.ipynb`](./notebooks/matplotlib/bar-charts.ipynb) | Designing horizontal and grouped vertical bar charts for categorical comparisons. |
| 🧱 [`histogram.ipynb`](./notebooks/matplotlib/histogram.ipynb) | Plotting frequency distributions and binning continuous data. |
| 🍕 [`pie-chart.ipynb`](./notebooks/matplotlib/pie-chart.ipynb) | Visualizing proportional/part-to-whole relationships with pie charts. |
| 🎨 [`format-string.ipynb`](./notebooks/matplotlib/format-string.ipynb) & [`legend.ipynb`](./notebooks/matplotlib/legend.ipynb) | Customizing line markers, colors, styles, grid lines, and adjusting legends. |

---

### 4. 🧮 Statistical Mathematics
Mathematical and statistical computations including outlier detection, transformations, and hypothesis testing.

| Notebook | Topic / Description |
| :--- | :--- |
| 📐 [`mean-median.ipynb`](./notebooks/stat-math/mean-median.ipynb) | Basic measures of central tendency and how outliers skew summary statistics. |
| 📊 [`std-exr.ipynb`](./notebooks/stat-math/std-exr.ipynb) | Understanding dispersion, variance, standard deviations, and standard error. |
| 🔔 [`normal-d-zscore.ipynb`](./notebooks/stat-math/normal-d-zscore.ipynb) & [`modified-zscore.ipynb`](./notebooks/stat-math/modified-zscore.ipynb) | Normal distributions, calculating Z-scores, and using modified Z-scores (with median absolute deviation) for robust outlier detection. |
| 📉 [`log.ipynb`](./notebooks/stat-math/log.ipynb) & [`log-normal-distri.ipynb`](./notebooks/stat-math/log-normal-distri.ipynb) | Logarithmic scaling, normal vs log-normal distributions, and transforming right-skewed distributions. |
| 🧪 [`z-t-test.ipynb`](./notebooks/stat-math/z-t-test.ipynb) & [`anova.ipynb`](./notebooks/stat-math/anova.ipynb) | Parametric hypothesis testing (One-Sample/Two-Sample Z and T tests) and Analysis of Variance (ANOVA). |
| 📐 [`cosine-distances.ipynb`](./notebooks/stat-math/cosine-distances.ipynb) | Vector math, vector space similarities, and calculating cosine distance/similarity. |

---

## 🛠️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/VijayHatte/EDA-and-Statistical-Analysis.git
   cd EDA-and-Statistical-Analysis
   ```

2. **Set up a Virtual Environment (Optional but Recommended):**
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Start the Jupyter Notebook environment:**
   ```bash
   jupyter notebook
   ```

---

## 💾 Datasets Setup Guide

To run the notebooks successfully, please copy the required dataset CSV files from your local downloads into the `data/` folder of this project.

| Dataset File Name | Notebook Dependency | Description |
| :--- | :--- | :--- |
| `netflix_titles_2021.csv` | `netflix.ipynb` | Netflix catalog data |
| `cities_air_quality_water_pollution.18-10-2021 (1).csv` | `pollution.ipynb` | Global pollution indexes |
| `CardioGoodFitness.csv` | `treadmill.ipynb` | Customer profile tracking |
| `AmesHousing.csv` | `anova.ipynb` | Ames, Iowa housing data |
| `winemag-data-130k-v2.csv` | `z-t-test.ipynb` | Wine reviews & scores |
| `bhp.csv` | `std-exr.ipynb` | Real estate pricing |
| `heights.csv` | `normal-d-zscore.ipynb` | Heights dataset |
| `income (1).csv` & `income.csv` | `log-normal-distri.ipynb`, `mean-median.ipynb` | Population income metrics |
| `movie_revenues.csv` | `modified-zscore.ipynb` | Box office revenues |
| `nyc_weather.csv` & `weather_data.csv` | `intro.ipynb`, `handling-missing-data.ipynb` | Weather logging data |
| `revenue.csv` | `log.ipynb` | Corporate revenues |
| `stock_data.csv` | `read-write.ipynb` | Financial stock tickers |
| `vij.csv` | `pie-chart.ipynb` | Custom charting stats |
| `weather.csv`, `weather2.csv`, `weather3.csv` | `pivot.ipynb` | Temperature and weather logs |
| `weather_by_cities.csv` | `group-by.ipynb` | City-by-city weather statistics |