:black_large_square:# Crypto-Clustering


Using Unsupervised Learning topic to cluster cryptocurrencies by their performance in different time periods. Then plot the results to show the performance of the cryptocurrencies. Using Elbow Curve to find a an effecitve k variable in order to help clustering the data. Then clustering cryptocurrencies by using [**K-Means algorithm**](https://www.analyticsvidhya.com/blog/2021/04/k-means-clustering-simplified-in-python/) and [**PCA method (Principal Component Analysis)**](https://www.geeksforgeeks.org/principal-component-analysis-with-python/)

---

:black_large_square:## Technologies

This project leverages [python](https://www.python.org/) 3.7 with the pandas library. Also, using [Jupyter notebook](https://jupyter.org/) in order to organize the code frame.

---

:white_check_mark:## Usage

To use this application, simply clone the repository and open jupyter lab from git bash by running the following command:

```jupyter lab```

After launching the application, navigate ``crypto_investments.ipynb`` notebook in the repository. 

Then in your Jupyter notebook, import the required libraries and dependencies.

```
import pandas as pd
import hvplot.pandas
from path import Path
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA as RandomizedPCA
from sklearn.preprocessing import StandardScaler

```



:black_large_square:### *Example*


:one:***Elbow Curve using K-Means Algorithm***

![elbow_k](https://user-images.githubusercontent.com/94591580/153809002-ae77b85b-0ba3-4849-bf2e-17a91284acce.png)



:two:***Elbow Curve using PC***


![elbow_pca](https://user-images.githubusercontent.com/94591580/153809158-ae27b767-f91d-4587-944c-44fc312c0d8a.png)

:three:***Clustering using K-Means Algorithm***

![cluster_k](https://user-images.githubusercontent.com/94591580/153809342-a5ba3559-d2aa-4e27-887a-c2c8a478749e.png)


:four:***Clustering using PCA Algorithm***

![cluster_pca](https://user-images.githubusercontent.com/94591580/153809406-f28f19f8-9a1c-4c90-8764-1ba38bcc6700.png)

---

:black_large_square:## Contributors

[Nguyen Dao](https://www.linkedin.com/in/nguyen-dao-a55669215/)

daosynguyen21@gmail.com


---

:black_large_square:## License

MIT
