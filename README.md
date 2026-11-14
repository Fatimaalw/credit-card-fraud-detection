# Credit Card Fraud Detection

CDS 4003 – Data Science for Business Application (Final Project)

## Business Problem
Card fraud causes direct financial losses for banks and damages customer trust. Fraud is rare (0.173% of transactions in our dataset), so rule-based filters miss cases or block legitimate customers. We aim to build a model that identifies fraudulent card transactions accurately, so that suspicious transactions can be reviewed or blocked without disrupting legitimate customers.

## Team
| Name | GitHub username | Role |
|------|-----------------|------|
| Fatima Adeeb | Fatimaalw | Problem formulation, dataset search, Streamlit deployment, repository management |
| Amna Salem | mnaya4345-jpg | Data cleaning, EDA and feature engineering |
| Amna Juma | Amna1633 | Model development, tuning and evaluation |

## Dataset
- **Name:** Credit Card Fraud Detection
- **Provider:** Machine Learning Group, Université Libre de Bruxelles (ULB), with Worldline
- **Source:** https://www.kaggle.com/mlg-ulb/creditcardfraud
- **Licence:** Database: Open Database License (ODbL) v1.0; Contents: Database Contents License (DbCL) v1.0, as stated on the Kaggle dataset page (checked 14 November 2026; screenshot in `docs/`).
- **Size:** 284,807 rows x 31 columns (Time, V1-V28, Amount, Class)
- **Target:** `Class` (1 = fraud, 0 = legitimate); 492 frauds (0.173%)
- **How to obtain:** `creditcard.csv` is about 144 MB, above GitHub's 100 MB limit, so it is not stored in this repository. Download it from the Kaggle link above and place it next to the notebook (or in a `data/` folder). A small sample is provided in `creditcard_sample.csv`; it contains all fraud rows plus 5,000 random legitimate rows, so it is only for testing that the code runs.

## Repository Structure
```
credit-card-fraud-detection/
├── README.md
├── requirements.txt
├── CreditCard.ipynb          (data understanding and cleaning notebook)
├── creditcard_sample.csv     (small sample; full dataset not included)
├── .gitignore
└── docs/
    └── dataset_search_evidence.md   (dataset search log and alternatives)
```
Further notebooks, the Streamlit app (`app/`) and the saved model (`models/`) will be added in the next stages.

## How to Run
1. Clone the repository.
2. Install the requirements: `pip install -r requirements.txt`
3. Download `creditcard.csv` from Kaggle and place it in the same folder as the notebook (or in `(https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?utm_source=chatgpt.com)/`).
4. Open `CreditCard.ipynb` and run all cells from top to bottom.

## Project Progress
- [x] Stage 1: Business problem formulation
- [x] Stage 2: Data collection (see `docs/dataset_search_evidence.md`)
- [x] Stage 3: Data understanding and cleaning (`CreditCard.ipynb`)
- [ ] Stage 4: EDA and feature engineering
- [ ] Stage 5: Model selection and development
- [ ] Stage 6: Hyperparameter tuning and evaluation
- [ ] Stage 7: Deployment

## Results So Far
- The raw dataset has no missing values, negative amounts or invalid class labels, but contains 1,081 exact duplicate rows (19 of them fraud).
- After removing duplicates: 283,726 rows, of which 473 are fraud (0.167%) and 283,253 are legitimate.
- Outliers in `Amount` (31,685 rows by the IQR rule, 87 of them fraud) were kept because they may carry fraud signal.
- Modelling results will be added after Stages 5 and 6.

## Live App
Streamlit link to be added after deployment.
