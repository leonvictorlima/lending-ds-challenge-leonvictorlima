<p align="center">
  <img src="https://asset.brandfetch.io/idxzTTSpOe/id4FNnTzWW.svg" alt="Your Logo" width="200" />
</p>

# Data Science Coding Challenge

## Challenge Overview

Welcome to the Data Science coding challenge! This exciting challenge will put your data science skills to the test across four key areas: data preprocessing, exploratory data analysis, modeling, and model evaluation. You'll be working with a Credit Risk dataset, delving into real-world scenarios.

## Dataset Description

The dataset contains valuable insights into the repayment performance of loans and the characteristics of loan applicants at the time they requested the loan. It encompasses a diverse range of both numerical and categorical features that significantly influence credit decisions.

### Attributes:

- **Status of existing checking account**: Financial stability reflected by the applicant's existing checking account.
- **Duration in months**: The credit's duration, measured in months.
- **Credit history**: The applicant's credit history, revealing past credit behavior.
- **Purpose**: The intended use of the credit, such as for furniture, a car, or education.
- **Credit amount**: The requested credit amount.
- **Savings account/bonds**: Applicant's savings status, indicating financial resources.
- **Present employment since**: Duration of the applicant's current employment.
- **Installment rate in percentage of disposable income**: Portion of disposable income allocated to credit repayment.
- **Personal status and sex**: Personal status and gender of the applicant.
- **Other debtors / guarantors**: Presence of other debtors or guarantors associated with the credit.
- **Present residence since**: Duration of the applicant's current residence.
- **Property**: Type of property owned by the applicant.
- **Age in years**: Age of the applicant.
- **Other installment plans**: Presence of other installment plans.
- **Housing**: Type of housing the applicant resides in.
- **Number of existing credits at this bank**: Number of existing credits with this bank.
- **Number of Accounts**: Number of accounts held by the applicant.
- **Job**: The applicant's profession or job type.
- **Number of people being liable to provide maintenance for**: Number of dependents or individuals the applicant is responsible for.
- **Telephone**: Availability of a telephone for the applicant.
- **Foreign worker**: Indicates if the applicant is a foreign worker.
- **Credit risk**: Target variable indicating the loan's performance (1 = Good, 2 = Bad).

## Getting Started

To get started with the coding challenge, follow these steps:

1. Clone this repository to your local machine:
   ```sh
   git clone https://github.com/yourusername/lending-ds-challenge.git
   ```
2. Navigate to the project directory:
    ```sh
   cd data-science-challenge
    ```
3. Create and activate a virtual environment (optional but recommended):
    ```sh
    python -m venv myenv          # Create the virtual environment
    source myenv/bin/activate    # Activate the virtual environment (Linux/macOS)
    myenv\Scripts\activate       # Activate the virtual environment (Windows)
    ```
4. Install the required packages using pip:
    ```sh
    pip install -r requirements.txt
    ```
5. Launch Jupyter Notebook or JupyterLab through terminal/cmd:
    ```sh
   jupyter lab
   ```
6. Navigate to the your-work folder and open the your-code.ipynb notebook.
Write and execute your code for the challenge tasks. 

7. Document your findings and conclusions in this README file inside the your-work folder.
   

## Challenge Tasks

### Task 1: Data Preprocessing

1. Load the dataset and handle any missing values.
2. Convert categorical variables into numeric representations using one-hot encoding.
3. Split the data into features (X) and the target variable (y).

### Task 2: Exploratory Data Analysis (EDA)

1. Dive into the data to gain meaningful insights.
2. Visualize key features and their relationships with the target variable.

### Task 3: Model Selection and Training

1. Choose a suitable classification algorithm.
2. Split the data into training and testing sets.
3. Train the selected model using the training data.

### Task 4: Model Evaluation

1. Evaluate the model's performance on the testing data.
2. Compute essential evaluation metrics.
3. Interpret the results and provide insightful observations.

## Submission Guidelines

- Clone this repository to your local machine.
- Complete the tasks using a Jupyter notebook.
- Include thorough comments and documentation to clarify your thought process.
- Create informative visualizations for EDA and model evaluation.
- Push your code and relevant files to your GitHub repository.
- Summarize your approach and findings in a README.md file.

## Evaluation Criteria

Your performance will be assessed based on:

- Handling of missing data and data preprocessing.
- Depth and quality of exploratory data analysis.
- Selection and training of an appropriate classification model.
- Rigorous evaluation of the model's predictive power.
- Clarity, quality, and documentation of your code.
- Interpretation of results and insights provided.

## Further Instructions

- Complete the tasks and commit your changes to your branch.
- Submit a pull request when you're ready to present your solution.

Have a fantastic time exploring the data, building models, and showcasing your data science skills!

---

Created with ❤️ by SumUp's Lending Team
