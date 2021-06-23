Data Science challenge
================================================================================
This project aims to solve data science coding challenge for weather forcasting with multiple stations.
The project contains two major parts:
- Data clearning and Analysis
- Training and prediction using a machine learning technique



Install
--------------------------------------------------------------------------------
- [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)
  to setup our environment
- python 3.7

Environment setup:
--------------------------------------------------------------------------------

```bash
conda --version

# Clone the repo
git clone https://github.com/EyaRhouma/data-science-challenge.git
cd data-science-challenge

# Create a conda env
conda env create -f environment.yml
source activate weather_forecast

```

Useful links:
--------------------------------------------------------------------------------
* [1] [BigQuery](https://cloud.google.com/bigquery/docs/visualize-jupyter)

* [2] [Feature engineering for machine Learning](https://towardsdatascience.com/feature-engineering-for-machine-learning-3a5e293a5114)


Next Steps:
--------------------------------------------------------------------------------
* [1] Better feature engineering:
- Better Fill of Nan Value : Use the same probability distribution the no Nan entities follow for filling the latent variable
- Use Feature reduction to understand better the relationship between the features (UMAP- PCA)
* [2] Use TimeSeries cross-validation to split the data: Forward Chaining, K-Fold or Group K-Fold

* [3] We only used one simple NN architecture, This can be improved by making the NN more complexe (Adding more depth and width)
or by experimenting with XgBoost, RNN