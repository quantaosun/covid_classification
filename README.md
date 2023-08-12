# covid_classification

A model has been developed to analyze active small molecules related to COVID-19 and subsequently predict the behaviour of unknown molecules. Inputs and outputs are required to adhere to a specific CSV format, as elucidated in the provided example notebook.

## The two provided covid19 CSV files are downloaded from an AI competition  

[Baidu COVID19 prediction](https://aistudio.baidu.com/aistudio/competition/detail/1012/0/task-definition)

## Try it now

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/quantaosun/covid_classification/blob/main/classification_chemprop.ipynb)


## Here we used *chemprop* package for the model building and prediciton
https://github.com/chemprop/chemprop

## How to use

Directly execute all the codes in Google Colab, after modification of the files paths

1. Cick https://github.com/quantaosun/covid_classification/blob/main/classification_chemprop.ipynb
2. Clkic "Open in colab" icon.

3. ## What else it can do

While our focus has been on training the model for bioactivity, the approach can readily be adapted to other chemical properties, such as solubility. Additionally, although we've presented a classification model, with minor modifications, a regression model can also be implemented.

## Please cite the Chemprop paper if you find their algorithm useful in your research

This repository is one new example built on top of the Chemprop package, it utilises message-passing neural networks for molecular property prediction as initially described in the paper [Analyzing Learned Molecular Representations for Property Prediction](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.9b00237) and as used in the paper [A Deep Learning Approach to Antibiotic Discovery](https://www.cell.com/cell/fulltext/S0092-8674(20)30102-1) for molecules and [Machine Learning of Reaction Properties via Learned Representations of the Condensed Graph of Reaction](https://doi.org/10.1021/acs.jcim.1c00975) for reactions. Chemprop now also has its own dedicated manuscript: [Chemprop: Machine Learning Package for Chemical Property Prediction](https://doi.org/10.26434/chemrxiv-2023-3zcfl). Please cite original papers if Chemprop is helpful to your research.

**General introduction from Chemprop authors:** 
[slides](https://docs.google.com/presentation/d/14pbd9LTXzfPSJHyXYkfLxnK8Q80LhVnjImg8a3WqCRM/edit?usp=sharing)
