# Exercise 5: K-Means — Customer Segmentation

## Objective
Group wholesale customers based on their spending across product categories.

## Dataset
`data/raw/wholesale_customers.csv`

## Workflow
- Apply log1p transformation.
- Scale the six spending features.
- Compare cluster counts using the elbow method and silhouette scores.
- Fit a four-cluster K-Means model.
- Profile customer groups and describe spending personas.

## Current Results
- Selected lab configuration: K = 4
- K=4 silhouette with StandardScaler: 0.1885
- Best tested K with StandardScaler: K=2, silhouette 0.2903
- The required silhouette target >= 0.42 was not achieved.

## Notebook
`notebooks/05_kmeans_clustering.ipynb`

## Outputs
- `outputs/exercise5_customer_clusters.csv`
- `outputs/exercise5_cluster_profiles.csv`

## Limitation
The current clustering results do not meet the lab silhouette acceptance target.
