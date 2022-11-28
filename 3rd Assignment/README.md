This assignmnet consists of four parts:

- In the first part we had to load the data and then clean them and create the graph. Afterwards we had to check for removable edges delete them and then create a dataframe with unconnected and removable edges. Our final dataframe includes pairs of nodes and a value of 1 indicates the existence of a link between them and 0 indicates absence of link. 

- In the second part of this assignment we also had to check whether and how the precision, recall and accuracy change if we set different thresholds for the link prediction process based solely on the Jaccard Coefficient metric.

- In the third part we had to add the Jaccard Coefficient, Resource Allocation and Preferential Attachment metrics as features for each pair of nodes in our dataset. Then we used the metrics as features for link prediction with Random Forest Classifier and our model  achieved good results for accuracy.

- In the final part of this assignment we used Node2Vec to generate embeddings based on random walks along with different binary operators and then using Random Forest Classifier we compared the final accuracies.
