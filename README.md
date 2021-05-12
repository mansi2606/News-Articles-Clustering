# News-Articles-Clustering

The dataset “NewsArticles.json” has news articles of mixed topics including business, entertainment, politics, sports, technology, but without labels. 
*We are working to make a clustering-based model without the use of NLP i.e. purely Machine Learning based. *

# Tasks to Perform
* Perform K-Means clustering on the above dataset and find the value of Sum of Squared Error (SSE)
* Use PCA algorithm to reduce the dimension of the dataset (about 100) and then perform K-means clustering on the manipulated dataset and find the value of Sum of Squared Error (SSE)
* Find the cluster having the highest value of count (before PCA). Also,
* Mention the highest value of count (before PCA)
* Find the cluster having the highest value of count (after PCA). Also,
* Mention the highest value of count (after PCA)
* Extract top 50 words from each cluster in both the cases and print the last word (50th word) from the cluster you think is of news articles related to the topic of entertainment (before PCA)
* Extract top 50 words from each cluster in both the cases and print the last word (50th word) from the third cluster (after PCA)   

**In both the above cases, we use the number of clusters as 5 and compute Sum of Square Error within clusters.

## Prerequisites

#### Installing Python

Make sure that you have [Python installed](https://realpython.com/installing-python/) on your machine.

You might want to use [venv](https://docs.python.org/3/library/venv.html) standard Python library
to create virtual environments and have Python, `pip` and all dependent packages to be installed and 
served from the local project directory to avoid messing with system wide packages and their 
versions.


#### Launching Jupyter Locally

All demos in the project may be run directly in your browser without installing Jupyter locally. But if you want to launch [Jupyter Notebook](http://jupyter.org/) locally you may do it by running the following command from the root folder of the project:

```bash
jupyter notebook
```
After this Jupyter Notebook will be accessible by `http://localhost:8888`.

#### Launching Jupyter Remotely

Each algorithm section contains demo links to [Jupyter NBViewer](http://nbviewer.jupyter.org/). This is fast online previewer for Jupyter notebooks where you may see demo code, charts and data right in your browser without installing anything locally. In case if you want to _change_ the code and _experiment_ with demo notebook you need to launch the notebook in [Binder](https://mybinder.org/). You may do it by simply clicking the _"Execute on Binder"_ link in top right corner of the NBViewer.

![](./images/binder-button-place.png)

## Datasets

The dataset beign used can be found in the repository as a json file as "NewsArticles.json".
