# credit-card-fraud-detection
CDS 4003 Final Project – Credit card fraud detection
# Credit Card Fraud Detection

CDS 4003 – Data Science for Business Application (Final Project)

## Business Problem
[Write 2-3 sentences in your own words: card fraud causes losses for banks and
customers, fraud is rare (0.173% of transactions), and we build a model that
flags fraudulent transactions without blocking legitimate customers.]

## Team
| Name | GitHub username | Role |
|------|-----------------|------|
| [Name] | Fatimaalw | [e.g. data cleaning and EDA] |
| [Name] | [username] | [role] |
| [Name] | [username] | [role] |

## Dataset
- **Name:** Credit Card Fraud Detection
- **Provider:** Machine Learning Group, Universite Libre de Bruxelles (ULB), with Worldline
- **Source:** https://www.kaggle.com/mlg-ulb/creditcardfraud
- **Licence:** ODbL v1.0 as listed on Kaggle (to be confirmed on the Kaggle page; see `docs/`)
- **Size:** 284,807 rows x 31 columns (Time, V1-V28, Amount, Class)
- **Target:** `Class` (1 = fraud, 0 = legitimate); 492 frauds (0.173%)
- **How to obtain:** The file `creditcard.csv` is about 144 MB, which is above
  GitHub's 100 MB limit, so it is not stored in this repository. Download it from
  the Kaggle link above and place it in `data/creditcard.csv`. A small sample
  is provided in `data/` [add once uploaded].

## Repository Structure

credit-card-fraud-detection/
├── README.md
├── requirements.txt
├── data/ (sample data; full dataset not included)
├── notebooks/ (numbered notebooks, e.g. 01_data_understanding.ipynb)
├── docs/ (dataset search evidence, data dictionary)
├── src/ (helper scripts) [planned]
├── app/ (Streamlit app) [planned]
└── models/ (saved model) [planned]


## How to Run
1. Clone the repository.
2. Install the requirements: `pip install -r requirements.txt`
3. Download `creditcard.csv` from Kaggle and place it in `data/`.
4. Open the notebooks in `notebooks/` and run them from top to bottom.

## Project Progress
- [x] Stage 1: Business problem formulation
- [x] Stage 2: Data collection (see `docs/dataset_search_evidence.md`)
- [ ] Stage 3: Data understanding and cleaning
- [ ] Stage 4: EDA and feature engineering
- [ ] Stage 5: Model selection and development
- [ ] Stage 6: Hyperparameter tuning and evaluation
- [ ] Stage 7: Deployment

## Results
[To be added after modelling.]

## Live App
[Streamlit link to be added after deployment.]
