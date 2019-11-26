# Snake Classification using CNNs
This is a project done with Matthew Cockrocft for my Computer Vision course at Wits University.

## About the project
The project is to classify images of snakes by species. This was a challenge put out by [AIcrowd](https://www.aicrowd.com/challenges/snake-species-identification-challenge) in 2019. 

We only use the labelled training set for our project, which can be downloaded [here](https://s3.eu-central-1.amazonaws.com/aicrowd-static/datasets/snake-species-identification-challenge/train.tar.gz). (20 GB)

## Required packages
All code is written in Python and can be found in the [Jupyter Notebook](https://github.com/nishai/snake-classification-with-CNNs/blob/master/Snake%20Identification.ipynb) in the repository.

The following python packages are required:

* `numpy`
* `seaborn`
* `pandas`
* `matplotlib`
* `torch`
* `torchvision`
* `opencv-python`
* `PIL`
* `fastai`
* `scikit-learn`
* `pylab`
* `tqdm`


We also recommend a using a device with a Cuda-compatible GPU to train the models.

## Our results
The repo contains our [project report](https://github.com/nishai/snake-classification-with-CNNs/blob/master/CV%20Project%202.pdf), with a detailed analysis of the methodology and results.

We trained 3 pretrained CNNS, namely: `AlexNet`,  `ResNet-18` & `MobileNet-v2`. The per epoch training and validation loss, accuracy and f1-scores are contained in .csv files in the [results](https://github.com/nishai/snake-classification-with-CNNs/tree/master/results) folder. 
We observe the highest accuracy with `MobileNet-v2` as shown below:

![Validation F1-scores](https://github.com/nishai/snake-classification-with-CNNs/blob/master/graphs/val-f1.png)
