# A content-based recommender system based on MIND dataset

We have built a simple content-based recommender system based on MIND dataset which is used for predicting future clicking interacts between users and news appearing on the Microsoft News page. Our model uses embedding vectors for entities of title or abstract of one news from WikiIDdata (these are provided in the dataset itself) to create the item feature vector of the item for recommendation tasks.

In this model, we uses a Python library supporting *Apache Spark* for processing on big data called ***PySpark***. Making sure that you have the dataset MINDsmall (small version of MIND dataset) and PySpark installed at your local, change the path to the dataset in the notebook file and start exploring our system.
