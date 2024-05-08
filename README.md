# RADIO FREQUENCY SIGNAL CLASSIFICATION
## Overview on utilzing Deep Learning Nueral Network for RF Classification


[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Radio Signal clasification is important in military and civilian communications.The classification of modulation type( or any signal feature ) is important for authentic communication.Contributions are made by various authors around globe using classic and advanced methods.Emerging deep learning methodilogies provided great performance in classifiying complicated large RF data.
[RadioML] began investing on ML(Machine Learning) and DL(Deep Learning) implementaions on classification of RF signals since 2016.They provided open source datasets generated as part of the research on [Deepsig] portal.My work shows performance on existing RML model implemented with Residual Neural Network.I present performance outputs of model on all the datasets provided by Deepsig.The project work aims to provide prerequites one needs to ready before proceeding to design new models improving neural networks.It insists on improving robustness of model,rather than recreating models again and again.
 

## Inferences from Project Work

- Decision making on Infrastructure considerations, That is Memory, RAM required for the Dataset loading,Preprocessing and Model Prediction.
- Decision Making on choosing environment to compile python notebook.
- Dataset Loading,Model input and output Understanding.
- Understanding Datasets from variuos sources, Fitting Data to existing models.
- Recollecting and Emphasisng Machine Learning fundementals or parameters, to improve predictions of existing models


> Conclusions: New models are continously implemented.From the survey it is appearing that new models are  improved or extended versions of current network.The basic Neural network say, CNN and memory based NN is common among all the papers.Please refer to the report document.Inspite recreating for some new models , i would like to express the idea to reuse existing models.Predicting with existing models on various datasets , configuring model parameters retraining the model back with modified or preprocessed dataset.This flow stands on using ML fundementals like number of batches, shaping of dataset, Parameter considerations and ingnorance,Python hacks to predict models which can predict wide number of datasets and reusng the models.



## Usage
To execute on Local
```sh
pip install jupyter
cd Radio_Spectrum_Classification
jupyter nbconvert --to notebook --execute  Classification-CNN.ipynb [dataset] predit_model
```


## Environment

| Environment | ipy file |
| ------ | ------ |
| Google Colab | [https://drive.google.com/file/d/1DfGVugM3GUrv3ZrTKiajQaqu4l646q3f/view?usp=sharing][PlGd] |





   [Deepsig]: <https://www.deepsig.ai/datasets/>
   [RadioML]: <https://github.com/radioML/examples>
   
 **Datasets are provided at [Deepsig]**

