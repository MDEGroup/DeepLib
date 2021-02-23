# DeepLib 

This repository provides the source code implementation of the tool and datasets used to perform evaluation for the following paper submitted to MSR 2021: 

DeepLib: Recommending Third-party Library Updates with Deep Neural Networks

## Introduction
We propose DeepLib, a novel approach to recommendation of an upgrade plan for software projects with respect to library usage. We mine migration history of projects
to build matrices, and use them to train deep neural networks, which have been specifically designed to cope with sequential data. The resulting network weights and biases are then used
to forecast the next versions of the related libraries for an input project.

<p align="center">
<img src="https://github.com/MDEGroup/DeepLib/blob/master/images/DeepLib.png" width="600">
</p>

## Folder tree

There are the following sub-folder:

* The [python_notebook](./python_notebook) contains the DeepLib tool:
	 **.ipynb** files contain the notebooks for running DeepLib.	
* The [LSTM](./LSTM) folder stores the dataset to evaluate DeepLib-alpha.	
* The [EncoderDecoder](./EncoderDecoder) folder stores the dataset to evaluate DeepLib-beta.	
	 In each of the dataset folder, there are ten sub-folders, i.e., *Roundi**, and each of them stores the training and testing data for one fold.
