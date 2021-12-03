# MSc DataScience

> Examples for the Big Data Mining class

## Install
- Create your virtual environment and install the required dependencies:

```
virtualenv -p `which python3` venv
source venv/bin/activate
pip install -r requirements.txt

# You will probably need to install a Jupyter kernel:
ipython kernel install --user --name=venv
``` 

Otherwise, copy and paste the scripts to Google Colab.


## Data preprocessing

- binning 
- correlation 
- feature selection 
- principal component analysis (PCA)
- normalization
- discretization with k means
- Exploratory data analysis (EDA)

## Classification

- decision trees for discretization, classification, rule extraction
- bayesian network
- SVM
- KNN

## Clustering

- clustering examples with K-means, hierarchical clustering and DBSCAN
- Silhouette coefficient examples

## Other

- data playground

## Data
The data folder contains various datasets and toy data used for the examples in this class.

## Notes
See requirements.txt to install the needed libraries in your virtual environment.
