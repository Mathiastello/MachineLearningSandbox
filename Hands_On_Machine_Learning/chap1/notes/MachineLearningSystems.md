# Types of Machine Learning Systems
>Machine Learning systems can be classified according to the amount and type of supervision they get during training. There are four major categories: supervised, unsupervised, semisupervisqed and reinforcement learning.

## Semisupervised Learning
>Most semisupervised learning algorithms are combinations of unsupervised and supervised algorithms. For example, *deep belief networks* (DBNs) are based on unsupervised components called *restricted Boltzmann machines* (RBMs) stacked on top of one another. RBMs are trained sequentially in an unsupervised manner, and then the whole system is fine-tuned using supervised learning techniques.

## Reinforcement Learning
>*Reinforcement Learning* is a repititive learning algorithm. The learning system, called an *agent*, can observe the environment select and perfrom actions, and get *rewards* or *penalties*. It must then learn by itself what is the best strategy, called a *policy*, to get the most rewards over time. A policy defines what action the agent should choose in a given situation.

## Batch and Online Learning
Another criterion used to classify Machine Learning systems is whether or not the system can learn incrementally from a stream of incoming data.

>### Batch Learning
>In batch learning, the system in incapable of learning incrementally: it must be trained using all the available data. This is generally done with *offline learning*.

>### Online Learning
>In *online learning*, you train the system incrementally by feeding it data instances sequentially, either individually or in small groups called *mini-batches*. Great for systems that receive data as a continuous flow and need to adapt to change rapidly or autonomously. Online learning can be used to train systems on huge datasets that cannot fit in one machine's main memory, called *out-of-core* learning.

## Instance-Based Versus Model-Based Learning
>### Instance-based Learning
>The system learns the examples by heart, then generalizes to new cases by using a similiary measure to compare them to the learned examples. 

>### Model-based learning
>Another way to generalize from a set of examples is to build a model of these examples and then use that model to make *predictions*. This is called *model-based learning*.


