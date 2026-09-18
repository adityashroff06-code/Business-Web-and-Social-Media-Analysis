# Business Web & Social Media Analysis — Coursework Portfolio

![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-EDA-150458?logo=pandas&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikitlearn&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

Complete coursework portfolio for **BUS 4023 — Business Web and Social Media Analysis** (George Brown College): five assignments applying Python-based analytics to classic business data-mining cases, from exploratory visualization through PCA, regression, and direct-marketing case studies.

## What's inside

| Folder | Case / dataset | Techniques |
|---|---|---|
| `Group Assignment_Case Study 1/` | **Charles Book Club** (`CBC.csv`) & **Tayko Software Cataloger** (Tayko) — two classic direct-marketing cases | RFM-style customer analysis, response modelling, targeting economics |
| `Case Study - 2/` | **eBay Auctions** (`eBayAuctions.csv`) — predicting competitive auctions | Classification case study (write-up in DOCX/PDF) |
| `In Class Assignment 2/` | Appliance shipments, riding-mower owners, laptop sales | Time-series line charts, scatter plots, boxplots, retail price comparisons across stores |
| `Weekly Assignment 3/` | Cereal nutrition, US universities (524 records), PCA exercise | Summary statistics, data cleaning, standardization, principal component analysis |
| `Weekly Assignment 5/` | **Boston Housing** & **Toyota Corolla** price data | Multiple linear regression, train/test evaluation (MAE/RMSE), prediction diagnostics |

Most cases come from *Data Mining for Business Analytics* (Shmueli et al.), the course's core text. Each folder contains the notebook(s) and, where produced, the written report (DOCX/PDF).

## Skills demonstrated

- **Exploratory data analysis** — profiling, missing-value handling, summary statistics
- **Business visualization** — choosing the right chart (line, scatter, boxplot, heatmap) to answer a business question
- **Dimensionality reduction** — standardization + PCA and interpreting component loadings
- **Predictive modelling** — linear regression with proper train/test splits and error metrics
- **Direct-marketing analytics** — response modelling and customer targeting on the Charles Book Club and Tayko cases
- **Communicating results** — accompanying written reports translate model output into business recommendations

## Running the notebooks

Most notebooks were developed in **Google Colab** and load their CSVs via `files.upload()` or a local path — when re-running, upload the CSV from the same folder (or fix the path to point at it).

```bash
git clone https://github.com/adityashroff06-code/Business-Web-and-Social-Media-Analysis.git
cd Business-Web-and-Social-Media-Analysis

python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

## License

Code released under the [MIT License](LICENSE). Course datasets remain the property of their respective publishers and are included for educational purposes only.

## Author

**Aditya Shroff** — [GitHub](https://github.com/adityashroff06-code) · [LinkedIn](https://www.linkedin.com/in/aditya-shroff-8033a31b0)
