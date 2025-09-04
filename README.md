# Social-Media-Bot-Detection-Using-Graph-Based-Features

🕵️ Social Media Bot Detection using Machine Learning & Graph Analysis

This project focuses on detecting automated accounts (bots) on social media by combining machine learning with graph-based community detection. The goal is to explore how user behavior and network structure can help distinguish bots from genuine human users.

🔎 Features
Built a user-user mention network using NetworkX.  
Extracted graph metrics: in-degree, out-degree, PageRank, betweenness centrality, clustering coefficient.  
Applied Greedy community detection to identify clusters of users.  
Combined behavioral features (followers, tweet frequency, etc.) with graph features.  
Trained and evaluated models: Logistic Regression and XGBoost.  

📊 Results

User-level features performed strongly.
Graph-based features added limited improvement.
Community detection features showed potential, highlighting abnormal clustering patterns of bots.

⚙️ Tech Stack
Python (pandas, numpy, scikit-learn)
NetworkX (graph construction + metrics)
XGBoost
Matplotlib/Seaborn (visualization)

🚀 Future Work
Explore advanced community detection methods (e.g., Louvain, Infomap).
Apply Graph Neural Networks (GNNs) for representation learning.
Include temporal activity patterns for improved detection.
