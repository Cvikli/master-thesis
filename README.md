# Thesis
Efficient model fitting of artificial neural networks.

### Explaining
This research's purpose is to automatize the process of finding the right model by filtering the wrong parameters those only describes the training dataset specific features and not valid in the general model.

It is a special generation based regularisation that observes the training process and like a human would do with a heuristics it evaluates the model parameters, determining the general correlations on the dataset in the specific model. 

### Short conclusion
This method is capable of decreasing the overfitting in an automatic way. 

### Document
The thesis is written in Hungarian. 
https://tdk.bme.hu/VIK/DownloadPaper/Mestergeges-neuralis-halok-modellenek-javitasa 

### Used technology
+ Tensorflow
+ Python (for fast prototyping)

### Algorithm limits/conditions
+ There must be some kind of overfitting between the train and validation dataset (that is what it decrease automatic way.)
+ The arithmetic used in the neural network is limited (It can be extended.)
..* e.x. recurrence node needs some work to be handled properly
+ Batch based training isn't adequate

# Results
The prototype was able to decrease overfitting on test datasets by order of magnitude:
[results will come here]
