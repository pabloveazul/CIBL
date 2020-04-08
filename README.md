# CIBL
This repository corresponds to the jupyter scripts of the CIBL-utterance classification project done with the Center for Advanced Research in Education, Institute of Education (CIAE) of Chile and our finnish associates from the University of Jyväskylä. The description of each script follows:
 
1. Data Statiscis: basic statistics of the data-base concerning the utterances distribution and word frequency.
2. Word Embedding Models: implementation of the word embedding models.
3. Model Evaluation: sequential evaluation of the different models and accuracy analysis, mean confusion matrix and vizualizations.

Also you can find some other analysis like:

4. Entropy Analysis: entropy analysis of the attention/final classification outputs.
5. Inter-Rater Analysis: analysis of model performance with data labeled by two different human coders.
6. Attention Models and Attention Plots: some more attention models and attention vizualization.

In order to use these codes follow the following steps:

1. Create a working folder, it's path should be set as the 'local_path' variable in the scripts
2. Create the 'models', 'models_wegihts' and 'Results' folders inside
3. Inside the 'Results' folder, create the 'Accuracy' and 'Comparative' folders
4. Inside the 'models' folder, create the 'Evaluation' folder
5. Have fun

The 'pe_dif_at' model's architecture and weights after evaluation process .h5 files are added in this github. 
