# 2019_Bookdown

### Nutrient Diagnosis Of Potato (*Solanum tuberosum L.*) Using Ionomics And Cultivar Classification

## Abstract

As new potato (*Solanum tuberosum L.*) cultivars are being developed and assigned to maturity groups, proper nutrient management still requires expensive fertilizer trials. The science of ionomics that relates tissue nutrient profiles to genetics provides continuous variables reflecting differential nutrient status and tuber yield potentials. Our objective was to predict potato tuber yield using ionome and a novel classification attribute that assigned cultivars to groups for diagnostic purposes. The dataset comprised 199 potato N, P and K fertilization trials where first mature leaves from top were sampled at the beginning of flowering for N, P, K, Ca, and Mg analysis. Nutrient concentrations (ionomes) were preprocessed by adjusting each nutrient to the geometric mean of all nutrients and to a filling value producing a row-centered log nutrient multiratio. The cultivars were clustered into ionomics groups using unsupervised learning. Groups allowed testing whether a supervised learning model of tuber marketable yield could return higher predictive accuracy compared to the current classification of potato cultivars into maturity groups. Four groups were obtained from a cascade k-means function computed across cultivar ionome centroids. The clrs that dominated group discrimination were K, Mg and N. Each novel group represented several maturity classes, indicating divergence between ionome clusters and maturity classes. Combining ionomic groups and *clr* variables as predictors, all the machine learning models returned similar yield prediction accuracies averaging 72% on testing data set. The models performed better for some cultivars with a predictive accuracy higher than 75%. We suggest addressing differential nutrition of potato cultivars objectively by possibly combining ionomes and ionomics groups rather than maturity classes. Ionomes of new cultivars could be assigned to the closest healthy ionomic group where nutrient requirements have been already documented by fertilizer trials.


[Access Book](https://rgoals.github.io/2019_Bookdown/) and [R codes](https://github.com/rgoals/2019_Bookdown), or use table of contents below.


## Contents

[Chapter 1 Data processing](https://rgoals.github.io/2019_Bookdown/index.html)

[Chapter 2 Cluster analysis of potato cultivars](https://rgoals.github.io/2019_Bookdown/Chapter-Clustering.html)

[Chapter 3 Predicting tuber yield category](https://rgoals.github.io/2019_Bookdown/Chapter-Modeling.html)

[Chapter 4 Perturbation vector theory](https://rgoals.github.io/2019_Bookdown/Chapter-Perturbation-vector.html)

[References](https://rgoals.github.io/2019_Bookdown/references.html)
