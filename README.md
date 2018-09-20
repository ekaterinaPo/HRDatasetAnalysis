# HR Dataset Analysis
## Objective
The main goal of this data science project is to determine reasons for attrition and why people leave companies. Also, I created the predict model to determine attrition.   

## Dataset
The analysis performed for this project uses a [Kaggle dataset](https://www.kaggle.com/shubham17mcb1015/hr-data/kernels). 
It contains 1,470 examples and 35 features (34 features and 1 binary response).  

## Analysis process
1. Understanding and cleaning data  
2. Determine the min, max and mean of the data, outlier analysis  
3. Correlation matrix  
4. ANOVA
5. Dummy variable  
6. Logistic regression: all columns, backward elimination and significant columns  
7. Plots and prediction  

## Results
Pseudo-R2 bigger when there are all variables in logistic regression, after deleting unsignificant (according to ANOVA test and those which p(z-test) > 0.05) Pseudo-R2 decreased.  
Accuracy of prediction is 0.886621315193  
Precision: No attrition - 0.894207 / Attrition - 0.818182  
Recall:    No attrition - 0.977961 / Attrition - 0.461538  

