# CMPE-256-Project-Repo
## Required Packages: 
    1. python version 3.6.10
    2. NetworkX
    3. Matplotlib (visualizations)
    4. pandas
    5. numpy
    6. random
    7. sklearn
    8. tqdm
    9. re
    10. Collections
    11. itertools
    12. Numpy
    13. Time
### Most Influential User
This file discusses about the four different algorithms to identify the most inflential users in the egoNode : 698.
Number of Nodes: 62 and
Number of edges: 331

#### Four algorithms implemented are:
    1. Degree Centrality
    2. Betweenness Centrality
    3. Closeness Centrality
    4. PageRank

### Link Prediction
The ‘Link Prediction’ folder has two .ipynb files- EgoNode-686 LinkPrediction and LinkPredictionModelEvaluation. The former contains the evaluation of link prediction model for EgoNode-686 and displays a few node pairs with a probability of link formation greater than 0.9. The latter contains the evaluation of our link prediction model for the entire SNAP Facebook dataset using the roc_auc_score metric.


### Community Prediction using Label Propagation

In the folder, Community_Prediction_LPA, there are 2 files as lpa_com_pred_total.ipynb which has the generation of graphs for both synchronous Label propagation and Asynchronous Label Propagation for all the ego networks present in the data set and Comm_pred_eval_metrics_py.ipynb has the community detection graphs, evaluation metrics for the 698 egonode along with the represntation of communities from the same ego network. 
To run the files, the first 2 cells are to be deleted if in a PC or works good in colab. Also, the path to the data should be set accordingly.

### Community Detection using Girvan-Newman and Lovain Algorithms

The folder 'Community Detection_Girvan-Newman_Louvain' contains following files:
1. Facebook : This folder contains all data files (.circles, .edges, .feat, .featnames, .egofeat )extracted from facebook.tar.gz 
2. Community_Detection_Grivan_Louvain.ipynb : This file contains the data extracts from Facebook files and constructs graphs for each ego-node and implements of community detection using Girvan-Newman and Louvain Algorihms and then evaluates the communities and plots the statistics.
3. read_egoNetwork.py : A Utility file that has functions designed to read circles, edges from files, construct and return graphs, read communities detected by algorithms. This file is imported to Community_Detection_Grivan_Louvain.ipynb
4. commdect_algos_eval.py : A utility file that has Girvan-Newman algorithm that returns communities, cost and loss functions for evaluating the communties detected and returns the score. This file is imported to Community_Detection_Grivan_Louvain.ipynb
5. plotGraphs.py : A Utility file that has functions designed to plot all types of graphs which include ego network plots, community detection plots, evaluation plots. This file is imported to Community_Detection_Grivan_Louvain.ipynb
6. Images : This folder contains all images related to ego-networks, community plots and evalautions results.
    
    
