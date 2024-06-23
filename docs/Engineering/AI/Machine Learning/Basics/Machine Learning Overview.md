# What is Machine Learning?

Machine Learning is the field of study that gives computer the ability to learn without being explicitly programmed. Practically, we are at the stage that we gives data for a algorithm to learn from and we test its performance by a measurement of measure.

For example, a spam filter is a Machine Learning problem that can learn to flag spam given examples of spam emails and identify regular emails. The data that's used to learn is called *training set*, each training example in the training set is called a *training instance* or simply *sample*. In case of classification task, we may use *accuracy* to measure how correct it classified a spam email.

Benefit of using machine learning algorithms instead of regular algorithms is that we do not need to specify the rules for a task explcitly. We just need to feed datas to the machine learning algorithm. Any unnoticed rules that should specify for regular algorithms can be omitted by machine learning algorithms due to the fact that machine learning algorithms are rules independent but data dependent. Any flutuations from the environment will be observed by the machine learning algorithm.
# Classification of Machine Learning tasks.

In General, we can classify a machine learning system by the following:
1. The necessacity of a human assistant. (Supervised learning, unsupervised, semisupervised, reinforcement)
2. The ability to learn to learn continuous and quickly. (Online, Batch)
3. The ways they generalized the observations (Instance-based, model-based)
 

 ## Necessacity of a human assistant

 There are four major categories of how the machine learning systems trained. Supervised learning, unsupervised learning, semisupervised learning, and reinforcement learning.

 ### Supervised learning

A supervised learning requires each training instance in the training set that feeds to the algorithm includes their output (or *label*). Common tasks include classification (predicting classes) and regression (predicting values).

Examples algorithms include:
- k-Nearest Neighbors (knn)
- Linear Regression
- Logistic Regression
- Support Vector Machines (SVM)
- Decision Tree and Random Forest
- Neural networks

### Unsupervised learning

A unsupervised learning do not requires any instance from the training set with a label. Common tasks include grouping pattern (clustering), visualizing high dimensional datas preserving or without losing too much of their structures (dimensionality reduction), anomaly detection, and rule learning.

Example algorithms include:
- Clustering
  - k-Means
  - Hierarchical Cluster Analysis (HCA)
  - Exception Maximization
- Visualization and Dimensionality reduction
  - Principal Component Analysis (PCA)
  - Kernal PCA
  - Locally-Linear Embedding (LLE)
  - t-distributed stochasic Neighbor Embedding (t-SNE)
- Rule learning
  - Apriori
  - Eclat

### Semisupervised learning

A semisupervised learning deal with partially labeled training data. Those algorithms are called semisupervised learning. For example, photo-hosting services, such as posting photo in Facebook. You upload all your family photos to the service, it automatically recognize the same group of person shown up in some photo. Clustering algorithms helps grouping those group of people into individual class, and once the user name one people in the group, then the algorithm recognize that person in the rest of the photos.

Example algorithms include:
- Deep belief networks (DBNs), algorithm based on unsupervised components called restricted Boltzmann machines (RBMs)

### Reinforcement Learning





