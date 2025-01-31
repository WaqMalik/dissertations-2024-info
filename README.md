# dissertations-2024-info

This is the repository for the 2024 Informatics MSc dissertations.
**Initial Investor Data Processing and EDA.ipynb**
Required Files:
investors.csv
investments.csv
funding_rounds.csv
Short Description. Dataframe and CSV creation
Output Files: investments_investors_funding_geo2.csv

**Initial Geo Data Processing and EDA.ipynb**
Name: Initial Geo Data Processing and EDA
Required Files: investments_investors_funding_geo2.csv (Created in Initial Investor Data Processing and EDA.ipynb)
Short Description: This notebook performs initial data processing and exploratory data analysis (EDA) on geographical data.
Output Files: processed_geo_data.csv
merged_df

**Initial Sector Data Processing and EDA.ipynb**
Name: Initial Sector Data Processing and EDA
Required Files:
investors.csv
investments.csv
funding_rounds.csv
organizations.csv
investments_investors_funding_geo2.csv (Created in Initial Investor Data Processing and EDA.ipynb)
Short Description: This notebook performs initial data processing and exploratory data analysis (EDA) on sector data.
Output Files: normalized_sector_grouped_investors.csv

**Geo-Kmeans w Maxabs.ipynb**
Name: Geo-Kmeans w Maxabs
Required Files: merged_df created in Initial Geo Data Processing and EDA.ipynb
Short Description: This notebook applies K-means clustering to geographical data using MaxAbs scaling.
Output Files: geo_kmeans_maxabs_clusters.csv

**Geo-Kmeans w Robust.ipynb**
Name: Geo-Kmeans w Robust
Required Files: merged_df created in Initial Geo Data Processing and EDA.ipynb
Short Description: This notebook applies K-means clustering to geographical data using Robust scaling.
Output Files: geo_kmeans_robust_clusters.csv

**Geo-Kmeans w Zscore.ipynb**
Name: Geo-Kmeans w Zscore
Required Files: merged_df created in Initial Geo Data Processing and EDA.ipynb
Short Description: This notebook applies K-means clustering to geographical data using Z-score scaling.
Output Files: geo_kmeans_zscore_clusters.csv

**Geography Agglomerative clustering.ipynb**
Name: Geography Agglomerative Clustering
Required Files: merged_df created in Initial Geo Data Processing and EDA.ipynb
Short Description: This notebook applies Agglomerative clustering to geographical data.
Output Files: geo_agglomerative_clusters.csv

**Geography DBScan clustering.ipynb**
Name: Geography DBScan Clustering
Required Files: merged_df created in Initial Geo Data Processing and EDA.ipynb
Short Description: This notebook applies DBScan clustering to geographical data.
Output Files: geo_dbscan_clusters.csv

**Geography Kmeans clustering.ipynb**
Name: Geography Kmeans Clustering
Required Files: merged_df created in Initial Geo Data Processing and EDA.ipynb
Short Description: This notebook applies K-means clustering to geographical data.
Output Files: geo_kmeans_clusters.csv


**Sector Agglomerative Algorithm.ipynb**
Name: Sector Agglomerative Algorithm
Required Files: normalized_sector_grouped_investors.csv (Created in Initial Sector Data Processing and EDA.ipynb)
Short Description: This notebook applies Agglomerative clustering to sector data.
Output Files: sector_agglomerative_clusters.csv

**Sector DBSCAN algorithm.ipynb**
Name: Sector DBSCAN Algorithm
Required Files: normalized_sector_grouped_investors.csv (Created in Initial Sector Data Processing and EDA.ipynb)
Short Description: This notebook applies DBScan clustering to sector data.
Output Files: sector_dbscan_clusters.csv

**Sector Kmeans Algorithm.ipynb**
Name: Sector Kmeans Algorithm
Required Files: normalized_sector_grouped_investors.csv (Created in Initial Sector Data Processing and EDA.ipynb)
Short Description: This notebook applies K-means clustering to sector data.
Output Files: sector_kmeans_clusters.csv
