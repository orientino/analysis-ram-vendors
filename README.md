## Data Mining 2020/2021
This project was developed during the Data Mining course [Department of Computer Science at University of Pisa](https://www.di.unipi.it/en/) under the supervision of professor [Anna Monreale](http://pages.di.unipi.it/amonreale/).

A project consists in data analysis based on the use of data mining tools. It has to be performed by using Python. The guidelines require to address specific tasks and results must be reported in a unique paper. The total length of this paper must be max 20 pages of text including figures. The students must deliver both: paper and well commented Python notebooks.

## Task 1: Data Understanding and Preparation
### Task 1.1: Data Understanding
Explore the dataset with the analytical tools studied and write a concise “data understanding” report describing data semantics, assessing data quality, the distribution of the variables and the pairwise correlations.

Subtasks of DU:
- Data semantics
- Distribution of the variables and statistics
- Assessing data quality (missing values, outliers)
- Variables transformations & generation
- Pairwise correlations and eventual elimination of redundant variables

### Task 1.2: Data Preparation 
Improve the quality of your data and prepare it by extracting new features interesting for describing the customer profile and his purchasing behavior. These indicators have to be extracted for each customer.

Once, the set of indicators will be computed the team has to explore the new features for a statistical analysis (distributions, outliers, visualizations, correlations).

## Task 2: Clustering Analysis
Based on the vendor’s profile explore the dataset using various clustering techniques. Carefully describe your decisions for each algorithm and which are the advantages provided by the different approaches.

Subtasks:
- Clustering analysis by K-means:
    - Identification of the best value of k
    - Characterization of the obtained clusters by using both analysis of the k centroids and comparison of the distribution of variables within the clusters and that in the whole dataset
    - Evaluation of the clustering results
- Analysis by density-based clustering:
    - Study of the clustering parameters
    - Characterization and interpretation of the obtained clusters
- Analysis by hierarchical clustering:
    - Compare different clustering results got by using different version of the algorithm
    - Show and discuss different dendrograms using different algorithms
- Final evaluation of the best clustering approach and comparison of the clustering
obtained

Explore the opportunity to use alternative clustering techniques in the library: https://github.com/annoviko/pyclustering/

## Task 3: Predictive Analysis
Consider the problem of predicting for each profile a label that defines if it is a big-seller vendor, small-seller vendor. The students need to:
1) define a vendor profile that enables the above vendor classification. Please,
reason on the suitability of the vendor profile, defined for the clustering analysis.
In case this profile is not suitable for the above prediction problem you can also
change the indicators.
2) compute the label for any vendor. Note that, the class to be predicted must be
nominal.
3) perform the predictive analysis comparing the performance of different models
discussing the results and discussing the possible preprocessing that they
applied to the data for managing possible problems identified that can make the
prediction hard. Note that the evaluation should be performed on both training
and test sets
 
## Task 4: Frequent Pattern mining and Association Rule Mining
Consider the problem of mining frequent common patterns of products bought together and extract the interesting association rules. Explore different parameters.

Optional (2 points): Study and compare the association rules of different geographical regions. One possibility is to consider the top regions or countries and compare the results obtained by mining patterns in each one.
