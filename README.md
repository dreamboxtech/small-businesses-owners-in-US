# Business Owners in US

In this project, I focused on business owners in the United States. We'll start by examining some demographic characteristics of the group, such as age, income category, and debt vs home value. Then we'll select high-variance features, and create a clustering model to divide small business owners into subgroups.

I used loop to build and train a K-Means model where n_clusters ranges from 2 to 12 (inclusive). 
The model includes a StandardScaler. Each time a model is trained, the inertia is calculated and added to a list, then the silhouette score is calculated and added silhouette_scores list.

I also made visualizations to highlight the differences between these subgroups.