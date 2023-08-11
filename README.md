# covid_classification
To train a model for covid active small molecule and then makes prediction for unknown molecules. 
All input and output are expected to be CSV files with a certain format, details see inside the example notebook.

## Here we used *chemprop* package for the model building and prediciton
https://github.com/chemprop/chemprop

## How to use

Directly execute all the codes in Google Colab, after modification of the files paths

1. Cick https://github.com/quantaosun/covid_classification/blob/main/classification_chemprop.ipynb
2. Clkic "Open in colab" icon.

3. ## What else it can do

   Though here we used the model to train bioactivity you could apply this to any other chemical property in a
   very similar way, for example, solubility.

   Also, here we only provide a classification model, the regression model is also supported with minor modification

## Please cite the Chemprop paper if you find their algorithm useful in your research

This repository is one new example built on top of the Chemprop package, it utilises message-passing neural networks for molecular property prediction as initially described in the paper [Analyzing Learned Molecular Representations for Property Prediction](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.9b00237) and as used in the paper [A Deep Learning Approach to Antibiotic Discovery](https://www.cell.com/cell/fulltext/S0092-8674(20)30102-1) for molecules and [Machine Learning of Reaction Properties via Learned Representations of the Condensed Graph of Reaction](https://doi.org/10.1021/acs.jcim.1c00975) for reactions. Chemprop now also has its own dedicated manuscript: [Chemprop: Machine Learning Package for Chemical Property Prediction](https://doi.org/10.26434/chemrxiv-2023-3zcfl). Please cite original papers if Chemprop is helpful to your research.

**General introduction from Chemprop authors:** 
[slides](https://docs.google.com/presentation/d/14pbd9LTXzfPSJHyXYkfLxnK8Q80LhVnjImg8a3WqCRM/edit?usp=sharing)
