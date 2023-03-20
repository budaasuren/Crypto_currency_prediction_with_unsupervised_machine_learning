# Crypto_currency_prediction_with_unsupervised_machine_learning

Used Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

Work Flow:
* Prepared the data using the StandardScaler() module from scikit-learn to normalize the data from the CSV file
* Found the best value for k using elbow method (the Original Scaled DataFrame)
* Clustered cryptocurrencies using the K-means model with the best value for k (the Original Scaled Data)
* Optimized Clusters with Principal Component Analysis(PCA) and reduced the features to three principal components
* Completed the same steps as the K-means model using the reduced features

Based on the results, we can conclude that we can use less features and get a similar performance to the original model since we can clearly identify the same number of clusters. However, in terms of the inertia, the PCA model performed better.

![Screen Shot 2023-03-20 at 10 42 23 AM](https://user-images.githubusercontent.com/113545468/226374939-0850cf79-f823-4aaa-b7b2-69a935853a44.png)

![Screen Shot 2023-03-20 at 10 43 28 AM](https://user-images.githubusercontent.com/113545468/226375135-24fca887-9d23-4252-b48e-42e196233c56.png)
