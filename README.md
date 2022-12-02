# COGS_118B_Project
Authors: Kyra Brandt, Chao-Li Wei (Michael)

## Motivation 
We chose a simulated customer segmentation problem for our project. Our simulated client is a Swiss medical device manufacturer who sells orthopedic devices worldwide. Company representatives work directly with individual doctors. According to the given scenario, the sales and customer support departments have historically grouped doctors according to their geographical region. However, as shown later, the region is not the best predictor of the number of purchases a doctor will make or their support needs.

We aim to use a data-centric approach, more specifically K-means clustering and dimensionality reduction, to better divide doctors into specific segments and develop spefically targeted approaches to improve marketing, customer service and product planning to each segment. We believe this will increase sales while making the sales and customer service departments more efficient, thus generating more profit.

## Reproduce Repository
* `pip install -r requirements.txt` to download all dependencies
To install ipykernal for jupyter notebook
* `pip install ipykernel` 
* `python -m ipykernel install --user --name=cog118b` 
* `jupyter-lab` in terminal to launch jupyterlab
## Notebooks
* `polished_notebook.ipynb` is the notebook that goes over our motivation, related work, methods, discussion, and conclusion
* `eda_notebook.ipynb` has the thorough analysis conducted used as a supplement to `polished_notebook.ipynb`. This notebook helps us pick the model hyperparameters and motivates the data aggregating and imputing methods we choose for `polished_notebook.ipynb`
 