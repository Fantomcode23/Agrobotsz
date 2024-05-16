# Agrobotsz
First we upload the preparation.py.In that file our datasets are separated based on the class labels.
Next we preprocessing the datasets.we started to blur and enhance the contrast image.
# Custom Optimizer: Archimedes
The Archimedes optimizer is a custom implementation of the RMSprop optimizer with additional features like momentum and centered gradient.
# SSAE
This model is then assembled by stacking the encoder and decoder Sequential models. It's compiled using the Archimedes optimizer with a learning rate of 0.001, and the loss function is categorical cross-entropy, suitable for multi-class classification problems. 
