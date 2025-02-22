# Unsupervised-Learning-Trade-Ahead  

Trade&Ahead is a financial consultancy firm who provide their customers with personalized investment strategies. They have hired you as a Data Scientist and provided you with data comprising stock price and some financial indicators for a few companies listed under the New York Stock Exchange. They have assigned you the tasks of analyzing the data, grouping the stocks based on the attributes provided, and sharing insights about the characteristics of each group.

## Skills and Tools Covered
* Clustering Techniques: K-Means Clustering, Hierarchical Clustering (Agglomerative)
* Exploratory Data Analysis (EDA): Data cleaning, Summary statistics, Feature distributions, Correlation analysis
* Data Processing: Scaling Techniques (Normalization, Standardization)
* Evaluation Methods: Elbow Method, Silhouette Score, Cophenetic Correlation
* Distance Metrics & Linkage: Euclidean, Manhattan, Single, Complete, Average, Centroid, Ward's Linkage
* Cluster Analysis: Sector-based segmentation, Distribution analysis, Cluster profiling
* Computational Considerations: Execution efficiency (K-Means vs. Hierarchical Clustering), Scalability
* Visualization Techniques: Elbow Method Visualization Tool (KElbowVisualizer), Silhouette Analysis (SilhouetteVisualizer), Dendrogram Analysis
* Tools & Libraries: Python, Scikit-Learn, Matplotlib, Seaborn, Pandas, NumPy, SciPy, Yellowbrick

## My Learning:
In this project, clustering techniques were applied to analyze stock market data, enabling better investment decision-making. Using financial indicators and stock prices from companies listed on the NYSE, the goal was to segment stocks into meaningful clusters based on shared characteristics.

The analysis involved two clustering methods: K-Means Clustering and Hierarchical Clustering (HC). For K-Means, the optimal number of clusters was determined using the elbow method and silhouette scores. For Hierarchical Clustering, various distance metrics, including Euclidean and Manhattan, were tested alongside different linkage methods such as single, complete, average, and Ward’s linkage. The cophenetic correlation coefficient was used to evaluate the clustering structures and identify the most effective metric-linkage combination. Additionally, dendrograms were analyzed to interpret hierarchical relationships and determine the best distance metric and the optimal number of clusters for segmentation.

Insights from both clustering techniques were used to develop stock segment profiles, allowing for a deeper understanding of stock relationships and aiding investors in aligning their strategies with data-driven market trends.
