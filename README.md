# OrcaCNN Sample Data

## Overview

This is a small collection of sample data of the type that will be used in the [OrcaCNN project](https://github.com/ESIPFed/gsoc/issues/17).  

The data used in the project will not be super-clean and ready to train a model as in many machine learning tutorials or Kaggle competitions. The data has undergone some preliminary cleaning and standardization, but will require some additional processing to achieve the best results.

Remember, the goal is create a model that is very good at identifying killer whale calls out of long audio clips.  Creating a classifier that can skillfully identify calls in the data is one of many required steps in a real-world tool.

## Data contents

Directories:

- `data/long_samples`: Longer samples of the raw data
- `data/training/negative`: Clips of negative samples
- `data/training/positive`: Clips of positive samples


The positive samples also include a json file with the class labels for each sample.  The label for the negative samples could just be treated as 'negative' or an equivalent.

## Some helpful links

Idea:

- [Humpback Whales using CNN](https://ai.googleblog.com/2018/10/acoustic-detection-of-humpback-whales.html)

Implementation ideas to get you started:

- [Using Tensorflow to do Audio Recognition](https://www.tensorflow.org/tutorials/sequences/audio_recognition)
- [Example using Keras](https://blog.manash.me/building-a-dead-simple-word-recognition-engine-using-convnet-in-keras-25e72c19c12b)
- [Example Keras repo for human speech](https://github.com/drscotthawley/audio-classifier-keras-cnn)

## Caveats

This is very unlikely to be a sufficient amount of data to train a skilled model, but is enough to get a sense of the data and the type of work involved.

## Data sources

Data is a combination of samples from [OrcaSounds](http://www.orcasound.net/) and [Dan Olsen](https://www.zegrahm.com/field-leaders/dan-olsen).
