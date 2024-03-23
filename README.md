# excel-adoption-analysis
## Data Preparation

The dataset includes an "Adoption" column, which indicates whether an animal outcome was an adoption or not. The column uses a formula to check the "Outcome Type" column and assigns a value of 1 if the outcome was "Adoption", and 0 otherwise. This allows for easy filtering and analysis of adoption data.

The formula used in the "Adoption" column is: =IF(D2="Adoption",1,0)

