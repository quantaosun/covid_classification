# covid_classification

A model has been developed to analyze active small molecules related to COVID-19 and subsequently predict the behaviour of unknown molecules. Inputs and outputs are required to adhere to a specific CSV format, as elucidated in the provided example notebook. This notebook is written based on [Chemprop](https://github.com/chemprop/chemprop)

## The two provided covid19 CSV files are downloaded from an AI competition  

[Baidu COVID19 prediction](https://aistudio.baidu.com/aistudio/competition/detail/1012/0/task-definition)

## Explore the COVID-19 Small Molecule Classification 

###  Molecules active against COVID-19 are labelled as '1', while all others receive a '0' designation.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/quantaosun/covid_classification/blob/main/classification_chemprop.ipynb)

## Example of output

```
Model 0 test auc = 0.932412
Model 0 test accuracy = 0.942515
Model 0 test binary_cross_entropy = 0.177413
Model 0 test f1 = 0.757576
Model 0 test mcc = 0.733754
Ensemble test auc = 0.932412
Ensemble test accuracy = 0.942515
Ensemble test binary_cross_entropy = 0.177413
Ensemble test f1 = 0.757576
Ensemble test mcc = 0.733754
1-fold cross validation
	Seed 0 ==> test auc = 0.932412
	Seed 0 ==> test accuracy = 0.942515
	Seed 0 ==> test binary_cross_entropy = 0.177413
	Seed 0 ==> test f1 = 0.757576
	Seed 0 ==> test mcc = 0.733754
Overall test auc = 0.932412 +/- 0.000000
Overall test accuracy = 0.942515 +/- 0.000000
Overall test binary_cross_entropy = 0.177413 +/- 0.000000
Overall test f1 = 0.757576 +/- 0.000000
Overall test mcc = 0.733754 +/- 0.000000
Elapsed time = 0:08:02
```

 ## What else it can do

While our focus has been on training the model for bioactivity, the approach can readily be adapted to other chemical properties, such as 

- solubility
- reaction energy barrier 
- spectrum wavelength

Additionally, although we've presented a classification model, with minor modifications, a regression model can also be implemented.


## Please cite the Chemprop paper if you find their algorithm useful in your research

This repository is one new example built on top of the Chemprop package, it utilises message-passing neural networks for molecular property prediction as initially described in the paper [Analyzing Learned Molecular Representations for Property Prediction](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.9b00237) and as used in the paper [A Deep Learning Approach to Antibiotic Discovery](https://www.cell.com/cell/fulltext/S0092-8674(20)30102-1) for molecules and [Machine Learning of Reaction Properties via Learned Representations of the Condensed Graph of Reaction](https://doi.org/10.1021/acs.jcim.1c00975) for reactions. Chemprop now also has its own dedicated manuscript: [Chemprop: Machine Learning Package for Chemical Property Prediction](https://doi.org/10.26434/chemrxiv-2023-3zcfl). Please cite original papers if Chemprop is helpful to your research.
