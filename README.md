# DeepLib 

This repository provides the source code implementation of the tool and datasets used to perform evaluation for the following paper: 

_DeepLib: Machine translation techniques to recommend upgrades for third-party libraries_

Phuong T. Nguyen, Juri Di Rocco, Riccardo Rubei, Claudio Di Sipio, Davide Di Ruscio

that has been accepted for publication with the Expert Systems with Applications Journal (ESWA), DOI: 
[10.1016/j.eswa.2022.117267](https://doi.org/10.1016/j.eswa.2022.117267).

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


## How to cite
If you find our work useful for your research, please cite the paper using the following BibTex entry:

```
@article{NGUYEN2022117267,
title = {DeepLib: Machine translation techniques to recommend upgrades for third-party libraries},
journal = {Expert Systems with Applications},
volume = {202},
pages = {117267},
year = {2022},
issn = {0957-4174},
doi = {https://doi.org/10.1016/j.eswa.2022.117267},
url = {https://www.sciencedirect.com/science/article/pii/S0957417422006388},
author = {Phuong T. Nguyen and Juri {Di Rocco} and Riccardo Rubei and Claudio {Di Sipio} and Davide {Di Ruscio}},
keywords = {Mining software repositories, Deep learning, Encoder–decoder neural network, Third-party libraries upgrade}
}

```


## Troubleshooting

If you encounter any difficulties in working with the tool or the datasets, please do not hesitate to contact us at one of the following emails: phuong.nguyen@univaq.it, juri.dirocco@univaq.it, riccardo.rubei@graduate.univaq.it, claudio.disipio@graduate.univaq.it. We will try our best to answer you as soon as possible.
