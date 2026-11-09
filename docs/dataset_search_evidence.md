# Dataset Search Evidence

Project: Credit card fraud detection (CDS 4003)
Search date: [date]
Searched by: [GitHub username(s)]
Search terms used: [e.g. "credit card fraud", "transaction fraud detection"]

## Requirements used to judge each dataset
- At least 200,000 rows and 20 columns
- Clear target variable for classification
- Licence allows academic use
- Real data (synthetic only with the instructor's written approval)
- Not used in previous coursework

## Search log

| # | Source | Dataset | Rows x Columns | Licence | Decision | Reason |
|---|--------|---------|----------------|---------|----------|--------|
| 1 | Kaggle | Credit Card Fraud Detection (ULB): kaggle.com/mlg-ulb/creditcardfraud | 284,807 x 31 | ODbL reported on Kaggle (an academic benchmark cites DbCL); to be confirmed on the Kaggle page | Selected | Real labelled transactions; meets the 200,000-row and 20-column requirement; clear target (Class); very imbalanced (0.173% fraud), which matches the business problem |
| 2 | Kaggle | IEEE-CIS Fraud Detection (Vesta): kaggle.com/c/ieee-fraud-detection | 590,540 x 394 (transaction table; identity table adds 41 more) | Kaggle competition rules | Considered, not selected | Rich features and many missing values, but use is governed by competition rules, which may restrict republishing data in a public repository and app; much larger and more complex to process |
| 3 | Kaggle | Simulated Credit Card Transactions, Sparkov (kartik2112): kaggle.com/datasets/kartik2112/fraud-detection | 1,296,675 x 23 (train file) | CC0 | Rejected | Synthetic data; the brief allows it only if no suitable real dataset exists and with the instructor's written approval |
| 4 | Kaggle | Fraud E-commerce (vbinh002) | about 151,000 rows | No licence stated | Rejected | Fewer than 200,000 rows and no clear licence |
| 5 | Kaggle | Home Credit Default Risk | 307,511 x 122 (team figures, to verify) | Competition rules | Rejected | Different business problem (loan default, not fraud) and competition-rule restrictions |
| 6 | Kaggle | Porto Seguro Safe Driver Prediction | 595,212 x 59 (team figures, to verify) | Competition rules | Rejected | Different business problem (insurance claims, not fraud) |
| 7 | Dubai Land Dept. / open data | Dubai Real Estate Sales Transactions | about 1,372,277 x 20 (team figures, to verify) | CC BY 4.0 | Rejected | Different business problem (property price prediction, not fraud) |
| 8 | UCI ML Repository | [dataset you found, or "no suitable fraud dataset found"] | | | | |
| 9 | Bayanat (bayanat.ae) | [dataset you found, or "no suitable fraud dataset found"] | | | | |

## Licence evidence
[Screenshot or exact licence wording from the Kaggle page on the download date]

## Prior-use check
[To be confirmed with the instructor: the dataset has not been used in previous coursework]
