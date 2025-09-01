# iris-kmeans-clustering
This project demonstrates unsupervised learning using the Iris dataset and K-Means clustering. It includes data visualization, elbow method for finding optimal clusters, and scatter plots to show results. The project highlights how K-Means can group similar flowers without labels.


# 🌸 Iris Dataset - KMeans Clustering

This project demonstrates **Unsupervised Learning** using the famous
**Iris Dataset** and the **K-Means Clustering** algorithm.\
The Iris dataset is a classic dataset in machine learning containing
measurements of iris flowers (Sepal & Petal dimensions).

We ignore the actual species labels and use **K-Means** to discover
natural clusters within the data.

------------------------------------------------------------------------

## 📊 Project Workflow

1.  **Load Dataset** -- Using `sklearn.datasets.load_iris()`\
2.  **Data Visualization** -- Pairplot (Seaborn) for initial data
    exploration\
3.  **Elbow Method** -- Determine the optimal number of clusters (using
    inertia)\
4.  **Apply KMeans** -- Cluster the dataset into groups\
5.  **Visualization** -- Scatter plots showing the clusters

------------------------------------------------------------------------

## 🛠️ Technologies Used

-   Python 🐍
-   Pandas\
-   Matplotlib\
-   Seaborn\
-   Scikit-learn

------------------------------------------------------------------------

## 📈 Results

-   The **Elbow Method** suggested **3 clusters**, which aligns with the
    actual number of species in the Iris dataset.\
-   The K-Means algorithm successfully grouped similar flowers together
    based on their measurements.

------------------------------------------------------------------------

## 🚀 How to Run

1.  Clone this repository\

2.  Install requirements (`pip install -r requirements.txt`)\

3.  Run the notebook:

    ``` bash
    jupyter notebook KMeans_iris.ipynb
    ```

------------------------------------------------------------------------

## 🔮 Future Improvements

-   Use **PCA** for dimensionality reduction and better visualization\
-   Try other clustering algorithms like **DBSCAN** or **Hierarchical
    Clustering**\
-   Compare clustering performance with supervised methods

------------------------------------------------------------------------

## 🙌 Acknowledgement

-   Dataset: [Iris Dataset (UCI /
    sklearn)](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)\
-   Algorithm: K-Means (Lloyd's Algorithm)

------------------------------------------------------------------------

⭐ If you like this project, don't forget to **star** the repo!
