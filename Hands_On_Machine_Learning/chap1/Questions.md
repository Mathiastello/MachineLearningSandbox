1) How would you define Machine Learning?
   * Formal Definitions
      * Machine Learning is the science and art of programming computers so they can learn from data
      * Machine Learning is the field of study that gives computers the ability to learn without being explicitly programmed
      * A computer program is said to elarn from experience E with respect to some task T and some performmance measure P if its performance on T as measured by P, improves with experience E.


2) Can you name four types of problems where it shines?
   * Problems for which existing sol;utions require a lot of fine-tuning or long lists of rules
   * Complex problems for which using a traditional approach yields no good solution
   * Fluctuating environemnts
   * Getting insights about complex problems and large amounts of data

3) What is a labelled training set ?
   * A labelled training set is a training set that contains the label. The label is the answer for what we are trying to solve. 
 Labelled training sets are generally used in Supervised learning.

4) What are the two most common supervised tasks?
   * Classification and Regression 
   * Most important supervised learning algorithms:
      * k-Nearest Neighbors
      * Linear Regression
      * Logistic Regression
      * Support Vector Machines
      * Decision Trees and Random Forests
      * Neural Networks (can also be semi supervised and unsupervised)

5) Can you name four common unsupervised tasks?
   * Clustering 
      * K-Means
      * DBSCAN
      * Hierarchical CLuster Analysis (HCA)
   * Anomaly detection and novelty detection
      * One-class SVM
      * Isolation Forest
   * Visualization and dimensionality reduction
      * Principal Component Analysis (PCA)
      * Kernal PCA
      * Locally Linear Embedding (LLE)
      * t-Distributed Stochastic Neighbor Embedding (t-SNE)
   * Assoication rule learning
      * Apriori
      * Eclat

6) What type of Machine Learning algorithm would you use to allow a robot to walk in various unknown terrains?
   * Reinforcement Learning 

7) What type of algorithm would you use to segment your customers into multiple groups?
   * Classification

8) Would you frame the problem of spam detection as supervised learning problem or an unsupervised learning problem?
   * supervised learning problem

9) What is online learning system?
   * Online learning systems are machine learning systems that have the ability to learn in increments. This is usually used for data that is streamed in like stock prices.

10) What is out-of-core learning?
   * When data is too large to learn/predict at once, out-of-core learning can take that static large dataset and learn piece by piece. This is usually done offline.

11) What type of learning algorithms relies on a similairty measure to make predictions ?
   * Instance based learning models work by 'memorizing' the trained data and apply a similarity function to new examples to make predictions

12) What is the difference between a model parameter and a learning algorithm's hyperparameter?
   * A model parameters allow the model the generalize new examples. Model parameters evolve when the model is learning and are fixed when they stop learning. A hyperparamter is a parameter of learning which belongs to the algorithm being used.

13) What do model-based learning algorithms search for ? What is the most commmon strategy they use to succeed? How do they make precitions?
   * Model-based learning algorithms search for an optimal value for the model parameters such that the model will generalize well to new instances. We usually train such systems by minimizing a cost function that measures how bad the system is at making predictions on the training data, plus a penalty for model complexity if the model is regularized. To make predictions, we feed the new instance's features into a model's prediction function, using the parameter values found by the learning algorithm

14) Can you name four of the main challenges in ML?
   * Main challenges in ML usually revolve around data. Insufficient quantity of training data, nonrepresentative training data, poor-quality data and irrelevant features are some of the challenges.

15) If your model performs great on training data but generalizes poorly to new instances, what is happening? Can you name three possible solutions?
   * When your model does well on training data but poorly on test data, the model is usually suffering from overfitting the training dataset. When this happens, we can simplify the model, constrain the models complexity, get more data, or add more meaningful features.

16) What is a test set and why do you want to use it?
   * A test set is a slice of the available data that is restricted to testing the model. You want to make sure your model doesn't see the test dataset before the learning as been completed. It is used to score your model after all tweaks.

17) What is the purpose of a validation set?
   * Validation datasets are used to evaluate model's performance, specifically under/overfitting characteristics.

18) What is the train-dev set, when do you nede it, and how do you use it?
   * The train-dev set is used when there is a risk of mismatch between the training data and the data used in the validation and test datasets. If the model performs well on the training set but not on the train-dev set, then the model is likely overfitting the training set. If it performs well onm both training set and train-dev set, but not on the validation set, then there is probably a significant data mismatch b.w the training data and the testing data (validation + test dataset)

19) What can go wrong if you tune hyperparameters using the test set?
   * If you tune hyperparameters using the test set, you risk overfitting the test set, and the generalization error you measure will be optimistic. 









