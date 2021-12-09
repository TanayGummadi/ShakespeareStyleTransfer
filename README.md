# ShakespeareStyleTransfer

## CS 4650 Final Project
### Rahul Bhethanabotla, Tanay Gummadi

This repository contains the necessary files to run the 4 models, `Seq2Seq`, `AttSeq`, `Transformer`, and `T5-Small`, discussed in the project paper.

### Directory Structure:

The `data` folder contains inputs and targets used for training and testing.

The `model_files` folder is used to cache the outputs of the `T5-Small` incuding the weights and tokenenizer.

The `models` folder contains the `.ipynb` notebook needed to run the project.

### Instructions:

Run the `Code.ipynb` file under the `models` folder one cell at a time to view the outputs of the various models within the notebook. 

The `T5-Small` configurations for weights and tokens will be generated into `model_files` and prediction outputs will be stored in a newly-generated file appearing in the parent directory as `predictions.csv`. 

