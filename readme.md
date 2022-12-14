## Decision Trees for hand gesture classification based on muscle activity data

In this project I implemented the ID3 decision tree algorithm from scratch and created a model that was able to predict hand gestures based on muscle activity. 

![grafik](https://user-images.githubusercontent.com/115760050/202944847-d408b360-328d-454a-942a-28eaf2272b1f.png)

The overall design of my algorithm follows object-oriented programming principles. I introduced two classes. First, the class DecisionTreeClassifier which includes all parameters and methods to build a tree and make a prediction with it. One instance of that class can be seen as one decision tree. The second class is called TreeNode and every instance represents a node of a decision tree. One DecisionTreeClassifier instance contains multiple TreeNode instances. The algorithm takes a dataset as input and returns a decision tree. The dataset has to be a multidimensional, homogeneous array of fixed-size items (e.g. numpy.ndarray) with decimal number values as items (e.g. numpy.float64). The decision tree is a list of connected TreeNode instances.

![grafik](https://user-images.githubusercontent.com/115760050/202944711-75a1ca80-39a3-4b12-a6b0-5704c86c7e77.png)

This project was created as part of the Advanced Data Analytics Algorithms subject at the University of Technology in Sydney.

Challenges: 
- Large high dimensional dataset
- Hyperparameter tuning because of long runtimes

Improvements:
- Restrict number of features considered for every split
- Dimensionality reduction
- Ensemble models (e.g. random forest)
