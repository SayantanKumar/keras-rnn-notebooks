# keras-rnn-notebooks
This repository contains iPython notebooks that demonstrate how to use the Keras library to build Recurrent Neural Network models for natural language processing tasks. There are three tasks and accompanying datasets: sentiment (review rating) prediction, language modeling (applied to text generation), and part-of-speech tagging. Each notebook is intended to stand alone as a demonstration, but there is a lot of redundancy between them in the code and documentation. These notebooks are probably most useful to people who have some experience with machine learning but are less familiar with how to apply machine learning to language-related tasks.

You'll need [IPython/Jupyter](https://ipython.org/) to run the notebooks, of course, or alternatively the regular Python files are provided. To run the code you'll need [Keras](https://keras.io/), as well as either [TensorFlow](https://www.tensorflow.org/) or [Theano](http://deeplearning.net/software/theano/) as the backend for Keras. You'll also need the data analysis library [pandas](https://pandas.pydata.org/), the NLP library [spaCy](https://spacy.io/), [Numpy](http://www.numpy.org/), [h5py](http://www.h5py.org/) (for saving models), and [scikit-learn](http://scikit-learn.org/) (for the evaluation metrics).

For each task, there is a dataset/ folder that contains example training and testing files for a larger dataset (to which the link is provided in the notebook). The notebooks load these example datasets and train an example model, which is saved to the example_model/ folder. The corresponding pretrained_model/ folder contains a model that has been previously trained on the full dataset, and the notebooks load these full models to demonstrate prediction and evaluation.

Feel free to provide feedback about any issues, or suggestions for what would be helpful: roemmele@ict.usc.edu.