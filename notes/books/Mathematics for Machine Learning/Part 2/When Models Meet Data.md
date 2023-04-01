- One guiding principle of machine learning is that good models must perform well on unseen data.
- Therefore, we must have a way to measure distance of the outputs of these models from ground truth with respect to the inputs.
- To this effect, there are three main components of machine learning.

## Data
- Usually represented as  a tensor.
- When represented as vectors, we usually call each vector a sample and entries in the vector features, attributes or covariates.
- In meaning learning, representing data in a meaningful is a key component to the field.

## Model
- This is predictive function that maps the inputs from data to an output, still in the data.
- This function are parametrize
- We can have models in two approaches.
	- Deterministic Function
	$$
f(\boldsymbol{x})=\boldsymbol{\theta}^{\top} \boldsymbol{x}+\theta_0
$$
	- Probabilistic Model: (Useful to measure noisy data)
		- This is model describing a distribution of possible functions7

## Learning
- This is a way to find the parameters of the models that correctly map input to output
- During this phase, the model adjust its parameter based on the data given
- In this phase, we do not just want a model performs well on the training data, but we also want a model that performs well on unseen data as well.
- Therefore, we need this balance of fitting on training data while keeping a simple approximation of the data.
- An agreed upon distinction between **parameters** and **hyper-parameters** is usually the distinction between what can be numerically optimized and what needs to be searched.
- Another to distinguish them is to take parameters as explicit parameters of the models and hyper-parameters as paramters that controls the distribution of these explict parameters