# Rule-Extraction_Trepan
The practical application of rule extraction as a possible strategy for explaining  black box models is 
investigated by implementing the TREPAN algorithm on a KNN model for the Classification of the iris flower 
dataset is investigated. The evaluation is performed by comparing of the classifications of the resulting 
decision tree with that of the KNN.


First of all, the preparation of the data is necessary. Since all features of the flowers consist of 
numerical values only the class had to be converted into a numerical value
Then, the dataset can be split into a training dataset and a test dataset in a 9:1 ratio.

The oracle is trained using a MultiLayerClassifier from Scikit-learn.
The optimal parameters are determined by a gridsearch crossvalidation (1 hidden layer with 5 nodes).

Afterwards the TREPAN algorithm can be trained.
