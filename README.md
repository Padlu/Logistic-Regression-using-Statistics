# Logistic-Regression-using-Statistics


**Experience Level:** Intermediate

**Technology Used:** R

**Skills Used:** --

---

#### Summary of the Experiment:

1. The aim of the experiment was to build a generalized Logistic Regression model on People's Satisfaction with their country Survey Data.
2. Above Survey Data is gathered from PEW Research Center website and meta data description of the variables is understood.
3. Descriptive statistics is performed to interpretate data well before diving into analysis.
4. Model is built with all the variables at first with train:test split of 80:20 using random sampling method. Having considered principal of parsimony and using p-value significance (Wald's Statistic) for the variables, the models are rebuilt by removal of insignificant variables with constant note of Null and Residual deviance. 
5. All assumptions of the Maximum Likelihood method of Logistic Regression is checked with diagnostics for model to be generalized.
      * Mutually Exclusive Dependent Variable
      * Reasonably High Sampling Size
      * Absence of Multicollinearity
      * Absence of Outliers
      * Independence of Errors
6. Model evaluation is performed by testing it on test set. Metrics used for evaluation are: Hosmer and Lemeshow Goodness-of-fit test, Accuracy, Deviance, Pseudo R^2, Sensitivity and Specificity.
7. Finally, model is interpretted using Odds Ratios of the final selected variables.
      

---

**Objectives of the Project:**
* Select the sample data from Pew Research website and apppropriate dependent and independent variables.
* Perform descriptive statistics on the data before modelling.
* Build a logistic regression model on the data and remove the insignificant variables if any for finalizing the model based on Wald’s Statistic.
* Perform diagnostic check on the final model.
* Evaluate the model based on comparison with null and predicted accuracy, Hosmer and Lemeshow goodness of fit test, Sensitivity and Specificity, Residual Deviance
and Pseudo Rˆ2 measures.
* Summarise and Interpret the final model and explanation
of Odds Ratio for all the variables.

---

### <ins>Data Description</ins>:

The Data is gathered from the Pew Research Center org. where the data is Survey data of Global Attitudes in Spring 2019.</br>
The Data was transformed to a complete sample dataset to perform regression by removing unanswered NULL entries. The data is sampled down from 22000 observations to 250 observations.</br>
Dependent Variable: Country Satisfation | selected as it was binary, mutually exclusive and exhaustive. </br>
Independent Variables: </br>
     1. Economy situation: Ordinal categorical variable | how good/bad country's economic situation is?</br>
     2. Children Better off: Binary variable | Are the children of the country better off/worse off financially in future?</br>
     3. Satisfied Democracy: Ordinal categorical variable | satisfation of the individual with the working manner of democracy in their country</br>
     4. Future Education: Binary variable | optimistic/pessimistic about education system of country</br>
     5. Market Economy: Ordinal categorical variable | Agreement of an individual to say most people do good in free market even though some are rich and some are poor.</br>
     6. Free Elections: Ordianl categorical variable: Importance of elections held being completely honest with a choice of at least 2 parties in the country.</br>
     7. Sex: Binary variable | Gender of an individual.</br>
     
### <ins>Descriptive Statistics</ins>:

Data: 250 observations | 7 independent variables | 1 dependent variable

![alt text](https://github.com/Padlu/Logistic-Regression-using-Statistics/blob/main/Images/Descriptive_stats.png "Descriptive Statistics")
