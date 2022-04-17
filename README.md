**<h1>Credit Risk </h1>**
<h2>Overview of analysis</h2>
<p> Using a dataset from LendingClub, a peer-to-peer lending service we are determining which algorithm best predicts credit risk. We will be using imbalanced-learn and scikit-learn libraries to build and evaluate models. Several algorithms including SMOTE, SMOTEENN, BalancedRandomForestClassifier, and EasyEnsembleClassifier.
<h2>Results</h2>
<p> Below, you will find the breakdown of each algorithm used. Focusing on a single value, in this case F1, helps me to identify where we would potentially find the best possible outcome. First, we need to know what an F1 score is. Simply put, it represents the model score as a function of precision and recall. What are we looking for? Low false positives, and low false negatives. 0 = bad, 1 = perfect. According to the example below, Balanced Random Forest appears to be the most reliable algorithm, with Easy Ensemble Classifier in a close second. 

<h3>F1 Weighted Average</h3>

  -	Naïve Random Oversampling = 0.74
  -	SMOTE Oversampling = 0.70
  -	Combination Sampling=0.72
  -	Balanced Random Forest= 1.0
  -	Easy Ensemble Classifier= 0.97

![results](https://github.com/SarahMason2015/Credit_Risk_Analysis/blob/df14225ba6090be1660ab61aebac7aee962d2715/Samples.png)

<h2>Summary</h2>
<p> Supervised machine learning is using datasets in order to predict outcomes accurately. There are many algorithms that can be used. In this dataset the most effective algorithm appears to be the Balanced Random Forest, followed by Easy Ensemble Classifier. Will this always be the best choice? Absolutely, not. Different data or different outcomes desired are among the many factors to decide what algorithm to use. 
