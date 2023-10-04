## NA values

No NA values were found!

## Dummy variables

There are different ways to use one-hot encoding. We can apply the Pandas get_dummies function or use the scikit-learn (sklearn) library. Below, we have both scenarios. In our approach, we will drop the first column based on the data observed up to this point.

## Task 2: Exploratory Data Analysis (EDA)

There are several libraries that can assist us in quickly obtaining data details, correlations, and variations. One of the most prominent libraries is Dataprep.

The Dataprep library facilitates exploratory analysis and combines various methods to help us extract valuable insights. Dataprep is available at https://dataprep.ai/ with documentation accessible at https://docs.dataprep.ai/index.html.

After carefully reviewing the relationships between the variables, we noticed that some variables are skewed. Another point of interest is that the library converted the data type of some numerical variables into categorical.

A noteworthy observation was made in the scatter plot distribution, where certain variations, such as 'duration in months' and 'credit amount,' show correlation.

Additionally, the target variable exhibits a good distribution between credit risk categories and is not an imbalanced variable, which is great!

Regarding this matter, we have examined the variables correlated with the target variable. You can find more details in script with the plots.


## Model Selection and Training

At this moment, we will create some base models using all available variables. Instead of using just one algorithm, we will employ three. While an essential aspect involves choosing the algorithm based on data distribution, the objective function, and other factors, for this project, we will follow the most common approach, which includes logistic regression, naive Bayes, and an ensemble model, Random Forest.

A good observation is that we do not have too much data, so the models will probably result in overfitting or underfitting.

## Evaluation and Results

The results indicate that our models performed bad because all metrics were perfect. This can be attributed to the limited amount of data available, which led to overfitting. Since there isn't much we can do about it, as machine learning models require a substantial amount of data, the models were unable to discern and establish a hypothesis function that accurately represents the data.
