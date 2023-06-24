# Decision-Tree-heart-disease-classification
A decision tree model that classifies whether one is prone to have heart disease in the next ten years or not based on different features. 

# Dataset
The dataset has been cleaned, and continuous and categorical data have been filled separately based on whether they're missing at random or not. Continuous features that aren't missing at random are filled in using "MICE" and ones missing at random are filled in with the mean. Both data types have been plotted using Seaborn and Matplotlib.

# Model
The decision tree model was first built without any pruning, the model was allowed to grow as much as possible and then it was tested. The model was then post-pruned using "cost-complexity-pruning" which allowed us to find the alpha value that results in the least node impurity. The model didn't show much improvement. To experiment more with the decision tree model, I then attempted pre-pruning, the model showed great improvement then. The overall accuracy turned out to be 85%. All decision tree models have been plotted in addition to the alpha impurity plot.
