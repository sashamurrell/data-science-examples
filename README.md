# data-science-examples

## Modelling incentives

Modelling the effect of incentives (such as price discounts) on customer behaviour, assuming customers are rational agents with a consistent reserve price over time. Defines a custom likelihood model for the model given data. Makes use of Markov Chain Monte Carlo using the Metropolis-Hastings  algorithm, in conjunction with data simulated under the model, to sample from the posterior distribution over unknown parameters related to the reserve price distribution. Compares the resulting posterior predictive distribution to the ground truth, investigating the effects of extending inference to unknown incentive sizes.

https://github.com/sashamurrell/data-science-examples/blob/master/NoiselessIncentivesModel.ipynb

<img src="https://user-images.githubusercontent.com/46842167/51708525-68c28200-2024-11e9-90cb-3e754b450f63.png" width="400">

## Autoencoder Visualization

Defining and training an autoencoder for images of handwritten digits, with an innermost encoder layer of dimension 2. Investigates the changes in the output as the number of training cycles increases, and the features of the innermost layer, both in terms of the encoding process (how images map onto 2D) and the decoding process (how 2D points map onto output images).

https://github.com/sashamurrell/data-science-examples/blob/master/VisualizingAnAutoEncoder.ipynb

<img src="https://user-images.githubusercontent.com/46842167/51709540-f56e3f80-2026-11e9-9e5c-9c917d7d1ba4.png" width="600">
