## What's In This Repo:

- This repository is for the heart disease classification research/model testing from kaggle data set 

- **Kaggle URL:** https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease?resource=download

## Heart_Disease_Classification:

- By using the data set provided by kaggle, I was able to explore key indicators of heart disease and create a classification model for whether or not an individual has heart disease. As the data set is fairly skewed, I try different methods of transforming my features in order to accurately predict 1 (heart disease) vs 0 (no heart disease). A few models explored within this experiment include decision tree, logistic regression, and naive bayes. Because this project was done during the beginning of my data science career, my methods are more simplistic in comparison to current work. 
- Some things to improve include the following:

  1. Fix sampling for training/test/val to either include more of the minority class (that being the population that does have heart disease) or decrease the sampling for the majority class (no heart disease)--over sample vs undersample to resolve the skewness/problematic curvature of classes (imbalanced data). 
  2. Tune the hyperparameters more in order to get the most optimal model as to not miss a potential heart disease case
  3. Feature Engineering: Combine some of the features or make other statistical evaluations to better describe the data (maybe bayes_prob of two really important features)
  4. Feature Training: Onehot encoding vs Ordinal encoding (impliment different transformations rather than just one) 
  5. Random Forest Classifier 
