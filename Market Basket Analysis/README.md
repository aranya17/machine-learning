Original Dataset : https://archive.ics.uci.edu/dataset/352/online+retail

Due to the large size of the original dataset (541909 records), which exceeded the available RAM and led to crashes during processing, I opted to work with a subset of the data for practical reasons. Specifically, we selected the first 5,000 records from the dataset.

**Rationale :**

System Limitations: The full dataset's size was too large to fit into memory, causing performance issues and system crashes.

Feasibility: Working with a smaller subset allowed us to perform data preprocessing and model training without encountering memory-related issues.


**Implications:**

Data Representativeness: While this subset was chosen arbitrarily (the first 5,000 records), efforts were made to ensure it is representative of the larger dataset. However, it is important to acknowledge that using a smaller subset may limit the generalizability of the findings.

Future Work: For a more comprehensive analysis, future work should consider techniques such as data sampling or chunk processing to handle larger datasets efficiently.
