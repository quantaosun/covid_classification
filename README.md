# covid_classification
To train a model for covid active small molecule and then makes prediction for unknown molecules. 
All input and output are expected to be CSV files with a certain format, details see inside the example notebook.

## Here we used *chemprop* package for the model building and prediciton
https://github.com/chemprop/chemprop

## How to use

Directly execute all the codes in Google Colab, after modification of the files paths

1. Cick https://github.com/quantaosun/covid_classification/blob/main/classification_chemprop.ipynb
2. Clkic "Open in colab" icon.

3. ## What else

   Though here we used the model to train bioactivity you could apply this to any other chemical property in a
   very similar way, for example, solubility.

   Also, here we only provide a classification model, regression model is also supported with minor modification
