# CMPE-256-Project-Repo
## Most Influential User
This file discusses about the four different algorithms to identify the most inflential users in the egoNode : 698.
Number of Nodes: 62 and
Number of edges: 331

#### Four algorithms implemented are:
    1. Degree Centrality
    2. Betweenness Centrality
    3. Closeness Centrality
    4. PageRank

## Link Prediction
The ‘Link Prediction’ folder has two .ipynb files- EgoNode-686 LinkPrediction and LinkPredictionModelEvaluation. The former contains the evaluation of link prediction model for EgoNode-686 and displays a few node pairs with a probability of link formation greater than 0.9. The latter contains the evaluation of our link prediction model for the entire SNAP Facebook dataset using the roc_auc_score metric.

#### Required Packages: 
    1. python version 3.6.10
    2. NetworkX
    3. Matplotlib (visualizations)
    4. pandas
    5. numpy
    6. random
    7. sklearn
    8. tqdm
    9.re
    

#In the folder, Community_Prediction_LPA, there are 2 files as lpa_com_pred_total.ipynb which has the generation of graphs for #both synchronous Label propagation and Asynchronous Label Propagation for all the ego networks present in the data set and #Comm_pred_eval_metrics_py.ipynb has the community detection graphs, evaluation metrics for the 698 egonode along with the #represntation of communities from the same ego network. 
#To run the files, the first 2 cells are to be deleted if in a PC or works good in colab. Also, the path to the data should be #set accordingly.
In the folder, Community_Prediction_LPA, there are 2 files as lpa_com_pred_total.ipynb which has the generation of graphs for both synchronous Label propagation and Asynchronous Label Propagation for all the ego networks present in the data set and Comm_pred_eval_metrics_py.ipynb has the community detection graphs, evaluation metrics for the 698 egonode along with the represntation of communities from the same ego network. 
To run the files, the first 2 cells are to be deleted if in a PC or works good in colab. Also, the path to the data should be set accordingly.
