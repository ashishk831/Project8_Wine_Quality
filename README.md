# Project8_Wine_Quality
Models to predict the quality of the wine.

In this notebook, First I have done some exploration on the data using matplotlib and seaborn. 
Then, I use different classifier models to predict the quality of the wine.

Dataset Description:
Variables:
1. Fixed acidity: most acids involved with wine or fixed or nonvolatile 
2. Volatile acidity: the amount of acetic acid in wine 
3. Citric acid: found in small quantities, citric acid can add 'freshness' and flavor to wines 
4. Residual sugar: the amount of sugar remaining after fermentation stops 
5. Chlorides: the amount of salt in the wine 
6. Free sulfur dioxide: the free form of SO2 exists in equilibrium between molecular SO2 (as a dissolved gas) and bisulfite ion 
7. Total sulfur dioxide: amount of free and bound forms of S02 
8. Density: the density of water is close to that of water depending on the percent alcohol and sugar content 
9. pH: describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic) 
10. Sulphates: a wine additive which can contribute to sulfur dioxide gas (S02) levels 
11. Alcohol: the percent alcohol content of the wine
12. Quality: output variable (based on sensory data, score between 0 and 10)

Libraries Involved:

1. Pandas 
2. Seaborn 
3. Matplotlib 
4. SVC 
5. SGDClassifier 
6. RandomForestClassifier

Steps Involved:

1. Import Package 
2. Load the Wine Dataset 
3. Plotting Graph 
4. Modeling

Conclusion:

Random forest accuracy increases from 87% to 91 % using cross validation score.
