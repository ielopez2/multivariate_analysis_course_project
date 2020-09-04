# multivariate_analysis_course_project
Final project looking at comparisons of PCA functions with their visualizations, interpretability and PC regression results, then conclude with comparisons to Factor Analysis loading results and Partial Linear regression results.

Using the “Risk Factors Associated with Low Infant Birth Weight” data set from the MASS package we will make comparisons. between two different Principle Component Analysis (PCA) functions using prcomp and princomp (the function learned in class), including visualisation comparisons using the factoextra package. We then will compare their interpretability and their PC regression results. We will also compare the interprtability of the PC functions with Factor Analysis as well as compare loadings and how implementing a varimax rotation affects both PCA and Factor Analysis loadings results.

During the section on regression methods, we will be predicting birth weight in grams of infants, comparing results using principle components calculated from prcomp() and princomp() as the feature variables. We will also explore comparisons with using the train model function to implement PC regression and partial linear regression, a method that has relevance with PC regression.

The R programming language will be used. Packages used in this project include MASS, caret, factoextra, corrplot, tidyverse, psych and GPArotation.
