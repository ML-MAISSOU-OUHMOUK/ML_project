# ML_project
Drug discovery in the fields of medicine and biotechnology, is the process in which new medications are discovered. However, drug development remains extremely expensive and time consuming. The new approaches concentrate on looking into preexisting Drugs and the possibility of using them in many new different treatments.
The prediction of drug-target interactions (DTI) is vital for drug discovery.
The goal of this project is to implement some Machine Learning methods to build a model that helps with the predictions of possible new interaction between drugs and proteins related to a certain disease in order to exploit these medications Using social network analysis.

### 1) Random Forest Classifier: 
A random forest is an estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting.
### 2) Logistic Regression: 
is a Machine Learning classification algorithm that is used to predict the probability of a categorical dependent variable. In logistic regression, the dependent variable is a binary variable that contains data coded as 1 (yes, success, etc.) or 0 (no, failure, etc.). In other words, the logistic regression model predicts P(Y=1) as a function of X.
# Evaluation: 
Besides the accuracy of the performance we are adding more evaluators in order to visualize and estimate the performance of our models. 
## F1 score :
The F1 score can be interpreted as a weighted average of the precision and recall, where an F1 score reaches its best value at 1 and worst score at 0. The relative contribution of precision and recall to the F1 score are equal. The formula for the F1 score is:
F1 = 2 * (precision * recall) / (precision + recall)
## Confusion Matrix :
It is a table that is often used to describe the performance of a classification model (or “classifier”) on a set of test data for which the true values are known. It allows the visualization of the performance of an algorithm.

## ROC curves :
ROC curves: typically feature true positive rate on the Y axis, and false positive rate on the X axis. This means that the top left corner of the plot is the “ideal” point - a false positive rate of zero, and a true positive rate of one. This is not very realistic, but it does mean that a larger area under the curve (AUC) is usually better.

# References:
1. Liben-Nowell D, Kleinberg J. The link-prediction problem for social networks. J Am Soc Inf Sci. 2007 May;58(7):1019–1031.
2. Gao F, Musial K, Cooper C, Tsoka S. Link prediction methods and their accuracy for different social networks and network metrics. Sci Program. 2015;2015:1–13.
3. Wang D, Pedreschi D, Song C, Giannotti F. Human mobility, social ties, and link prediction. Proceedings of the 17th …. 2011;
4. Lü L, Jin C-H, Zhou T. Similarity index based on local paths for link prediction of complex networks. Phys Rev E, Stat Nonlin Soft Matter Phys. 2009 Oct 26;80(4 Pt 2):046122.
5. Lü L, Zhou T. Link prediction in complex networks: A survey. Physica A: Statistical Mechanics and its Applications. 2011 Mar;390(6):1150–1170.
6. Ding Y, Yan E, Frazho A, Caverlee J. PageRank for ranking authors in co-citation networks. J Am Soc Inf Sci. 2009 Nov;60(11):2229–2243.
7. Mao G, Zhang N. Analysis of Average Shortest-Path Length of Scale-Free Network. J Appl Math. 2013;2013:1–5.
8. DrugBank 5.0: a major update to the DrugBank database for 2018. Wishart, David S., et al. Nucleic Acids Research. 2017.
9. MINER: Gigascale multimodal biological network. Stanford SNAP Group. GitHub Repository. 2017.
10. https://medium.com/@adityagandhi.7/network-analysis-and-community-structure-for-market-surveillance-using-python-networkx-65413e7b7fee
11. https://www.drugbank.ca
12. https://snap.stanford.edu/biodata/index.html
