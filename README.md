# Logistic-Regression-Model-for-Credit-Risk-Assessment
This project involves the analysis of the South German Credit Data from the University of California, Irvine (UCI) Machine Learning Repository. The dataset is designed to classify individuals as either good or bad credit risks based on a set of attributes.

## 📺 Project Description
Credit risk assessment is a fundamental process in the financial industry, crucial for evaluating the creditworthiness of individuals, companies, or entities seeking loans or credit agreements. Lenders, banks, financial institutions, and other credit providers rely on accurate assessments to make informed lending decisions. The objective of this GitHub project is to develop, implement, and share a Logistic Regression Model specifically designed for credit risk assessment.

### Challenges in Credit Risk Assessment

Credit risk assessment presents several challenges, including:

- **Data Complexity:** Credit data can be highly complex, often comprising a mix of numerical and categorical data. Dealing with this complexity requires advanced modeling techniques.

- **Dynamic Market Conditions:** Financial markets and economic conditions are constantly changing. Models need to adapt to new market dynamics and economic trends.

- **Imbalanced Data:** In many cases, good credit applicants significantly outnumber bad credit applicants. This class imbalance can make model training and evaluation tricky.

- **Model Transparency:** Given the legal and ethical implications of credit decisions, model transparency is essential. It should be possible to explain why a particular decision was made.

## Dataset Description
The "South German Credit" dataset contains 1000 records representing individuals who applied for loans at a German bank. It includes the outcome of these loan applications, indicating whether they were approved or not. The approval decision is based on the bank's assessment of the applicant's ability to meet their loan repayment obligations.

**Source:**
The dataset can be accessed on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/south+german+credit).

## Variable Information

This section contains a brief description for each attribute. 

| Column name | Variable name           | Content                                                |
|------------|-------------------------|--------------------------------------------------------|
| laufkont   | status                  | Status of the debtor's checking account with the bank (categorical)       |
| laufzeit   | duration                | Credit duration in months (quantitative)              |
| moral      | credit_history          | History of compliance with previous or concurrent credit contracts (categorical) |
| verw       | purpose                 | Purpose for which the credit is needed (categorical) |
| hoehe      | amount                  | Credit amount in DM (quantitative) |
| sparkont   | savings                 | Debtor's savings (categorical)                         |
| beszeit    | employment_duration     | Duration of debtor's employment with the current employer (ordinal; discretized quantitative) |
| rate       | installment_rate         | Credit installments as a percentage of debtor's disposable income (ordinal; discretized quantitative) |
| famges     | personal_status_sex     | Combined information on sex and marital status; categorical; sex cannot be recovered from the variable, because male singles and female non-singles are coded with the same code (2); female widows cannot be easily classified, because the code table does not list them in any of the female categories |
| buerge     | other_debtors           | Is there another debtor or a guarantor for the credit? (categorical) |
| wohnzeit   | present_residence       | Length of time (in years) the debtor lives in the present residence (ordinal; discretized quantitative) |
| verm       | property                | The debtor's most valuable property, i.e. the highest possible code is used. Code 2 is used if codes 3 or 4 are not applicable and there is a car or any other relevant property that does not fall under variable sparkont (ordinal) |
| alter      | age                     | Age in years (quantitative)                           |
| weitkred   | other_installment_plans | Installment plans from providers other than the credit-giving bank (categorical) |
| wohn       | housing                 | Type of housing the debtor lives in (categorical)     |
| bishkred   | number_credits          | Number of credits, including the current one the debtor has (or had) at this bank (ordinal, discretized quantitative; contrary to Fahrmeir and Hamerle's (1984) statement, the original data values are not available) |
| beruf      | job                     | Quality of debtor's job (ordinal)                     |
| pers       | people_liable           | Number of persons who financially depend on the debtor (i.e., are entitled to maintenance) (binary, discretized quantitative) |
| telef      | telephone               | Is there a telephone landline registered in the debtor's name? (binary; remember that the data is from the 1970s) |
| gastarb    | foreign_worker          | Is the debtor a foreign worker? (binary)              |
| kredit     | credit_risk             | Has the credit contract been complied with (good) or not (bad)? (binary) |


### Attributes
* 20 variables, including 3 continuous and 17 categorical attributes.
* Personal characteristics of individuals.
* Information about the loans they applied for.
* Customer's history of previous loans.
* A variable named "Credit Risk" (0 = bad, 1 = good) classifying customers as either good or bad payers.

**Preprocessing Steps:**

Before using the dataset for analysis and modeling, certain preprocessing steps were applied to ensure data quality and suitability for the project:

1. **Data Cleaning:** The dataset was examined for missing values, outliers, and inconsistencies. Any identified issues were addressed to prevent them from affecting the analysis and modeling.

2. **Encoding Categorical Variables:** As the dataset contains both numerical and categorical attributes, categorical variables were appropriately encoded to make them usable in the logistic regression model.

3. **Feature Selection:** A careful selection of relevant features was performed to avoid the inclusion of unnecessary variables that might negatively impact model performance.

### Project Contents
* Data Exploration: Utilize data analysis and statistics-based practices to gain insights into the South German Credit Data.
* Data Visualization: Create high-level and advanced statistical plots, including visualizations of correlations, outliers, and more.
* Data Curation: Process and cleanse the data to prepare it for modeling.
* Model Development: Build prediction models for credit risk assessment.
* Evaluation: Discuss computational results and assess model performance.

### Purpose
The main objective of this project is to build and evaluate a Logistic Regression model to predict credit risk. This model aims to assist financial institutions and lenders in making informed decisions when evaluating loan applications.


