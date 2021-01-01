# Main Challenges of Machine Learning
The two major things that can go wrong are bad algorithms and bad data.

## Insufficient Quantity of Training Data
[A famous paper](https://homl.info/6) stated that very different ML algorithms, including fairly simple ones, perfomred almost identically well on a complex progbral of natural language disambiguation once they were given enough data.

These results suggest that we may want to reconsider the trade off between spending time and money on algorithm development versus spedning it on corpus development.

The idea that data matters more than algorithms for complex problems was further popularized by this [paper](https://homl.info/7)

## Nonrepresentative Training Data
In order to achieve performant gneralizations, it is crucial that your training data be representative of the new cases you want to generalize to. This is oftern harder than it sounds: if the sample is too small, you will have *sampling noise*, but even very large damples can be nonrepresentative of the sampling method is flawd, called *sampling baised*.

## Poor-Quality Data 
Poor quality data is the biggest factor for underperforming models. Most data scientists spend the majority of their time cleaning up training data. Some common scenarios could be outliers and missing features.

## Irrelevant Features
*Feature Engineering* is the process of coming up with a good set of features to train on. Feature Engineering generally follows these steps:
* Feature selection
* Feature extraction (combining existings features to produce a more usefull one)
* Creating new features by gathering new data

## Overfitting the Training Data
A model that performs well on the training data, but it does not generalize well is a usually due to overfitting. Overfitting happens when the model is too complex relative to the amount and noiseness of the training data. Below are some possible solutions:
* Simplify the model by selecting one with fewer parameters
* Constrain the model to make it simpler (regularization)
* Gather more training data
* Reduce the noise in the training data

## Underfitting the Training Data
Underfitting occurs when your model is too simple to learn the underlying structure of the data. Below are some possible solutions:
* Select a more powerful model, with more parameters.
* Feed better features to the learning algorithm (feature engineering)
* REduce the constraints on the model (reduce regularization)


