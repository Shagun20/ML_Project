# Rainfall-Prediction-and-Analysis- Machine Learning 
Through this paper, we attempt to perform rainfall prediction using local weather data (Australia) for a Machine
Learning course project. Since the dataset has a target
variable that is of 0-1 classification type we train different
ML models on the dataset and compare the results and try
to understand the advantages and shortcomings for each
of the ones.
<br>
![image](https://github.com/Shagun20/Rainfall-Prediction-and-Analysis---ML/assets/85337809/e3a26f7c-9606-4b80-ab37-7e48bebb6b99)
<br><br>
After conducting the analysis, we observed that Gaussian Naive Bayes outperformed both Linear Models, including Support Vector Machines and Logistic Regression. On the other hand, the Non-Linear Models, namely Decision Tree, Random Forests, and AdaBoost, yielded even better results.
Specifically, for the Decision Tree, we found that the best-performing tree had a depth of 8 with a Gini Index, achieving a Precision of 82.6 percent. **The highest performance overall was achieved with AdaBoost, where the base model was the Decision Tree with depth 8 and Gini Index, with n-components set to 5**.
Regarding Regression, the Random Forest Regression model delivered the most promising results, while the Normal Linear Regression model performed the least satisfactorily among the three.





