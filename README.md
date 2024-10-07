# Text-Clustering-Based-On-Movies-Overview

## Background & Purpose
 • In recent years, the exponential growth of digital content has led to an 
abundance of textual information and the film industry is no exception. 

• Movie overviews, briefly summarizing the essence of films, represent a 
valuable dataset for exploration.

 • The background is rooted in the understanding that traditional methods of 
manual analysis are increasingly insufficient to harness the vast volume of 
textual data.

 • The purpose is to contribute to the evolving landscape of data analytics by 
employing advanced unsupervised learning techniques to extract valuable 
knowledge from unstructured textual data related to the domain of films.

## Aim
 • Leverage clustering algorithms on textual data related to the domain of 
films, specifically focusing on clustering movie overviews based on 
similarities in their textual descriptions in order to to extract meaningful 
insights from the dataset

## Solution Designs

### Data Preprocessing
 • Data Subset: The dataset is reduced to the first 15,000 entries for analysis.

 • Missing Values: Handling missing data, particularly in the overview column.
 
 • Text Cleaning: Implementing a function to clean the text data in the overview column. 
 
 • Tokenization: The cleaned overviews are tokenized 
 
 • Stopword Removal: Removing common stopwords 
 
 • Lemmatization: Converting words to their base or dictionary form.

 ### Feature Extraction
 •  TF-IDF Vectorization: Transforming the processed textual data into numerical form using TF-IDF vectorization. This step is critical for text clustering as it converts text into a format that machine learning algorithms can work with.

 • Dimensionality Reduction: Applying PCA to reduce thedimensions of the TF-IDF 
vectors, likely for better visualization and to alleviate the problem of dimensionality.

### Clustering
 •  Determining Optimal Parameters: Includes steps to find the optimal parameters for clustering algorithms. 
 
 i. K-Means Clustering - Elbow Method and KneeLocator Library.
 
 ii.Hierarchical Clustering - Dendrograms 
 
iii.DBSCAN - Nearest Neighbors algorithm

 •  Clustering Algorithms:  Fitting these algorithms to the processed data and interpreting the results.
 
 •  Silhouette Score: Calculating the silhouette score to assess the quality of the clusters formed.

 ### Results Visualization

 •  Visualize the cluster using scatter plots. This will help us understand how well the movies are clustered based on their overview.
