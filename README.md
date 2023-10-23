# BigBlue-Countries-Clustering
Repository for the 4th project on Unsupervised ML during my studies in Big Blue Data Academy Data Science &amp; Machine Learning Bootcamp 2023.  Goal of this project was to cluster countries based on socio-economic and health factors to determine the development of the country.

### Dataset used: [Countries Clustering🌎](https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data/data)
### About the Dataset:
#### Context📖:
["HELP International"](https://www.instagram.com/helpintl/) is a non-profit organization that focuses on alleviating poverty through sustainable, community-driven initiatives. Volunteers from this organization typically engage with communities in various countries, working on projects that focus on education, economic development, healthcare, and social issues. Countries will be clustered based on socio-economic and health factors, to determine the allocation of funds for assistance during disasters and natural calamities.

### Analysis & Results📊🕵🏻:
- Use of log transformation to normalize distribution minimize the impact of outliers and reduce heteroscedasticity even though it didn't work better in this example
- Outliers in this example represent unique cases of countries so they can actually help this clustering
- Is pretty obvious that the health factors have high correlations as well as the economic ones
- Clustering algorithms provide pretty discrete clusters that are very similar to the real-world situation
- There are differences between k-means & hierarchical clustering but not so significant
- Used PCA to visualize countries in each cluster in 2D,3D plots

### Conclusion✅🏁:
The main goal of the project was succeeded as the result of the Clustering is pretty close to [reality!](https://en.wikipedia.org/wiki/Developing_country#)
- This was actually a training dataset for clustering as it provides great results
- The EDA Section prepares you for this kind of discrete clusters and results. The quality of this dataset is pretty important in providing this output.

### [ View the Project's Notebook](https://nbviewer.org/github/DimBakogiannis/BigBlue-Countries-Clustering/blob/main/Countries%20Clustering.ipynb)
