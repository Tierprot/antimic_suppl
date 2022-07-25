# antimic_suppl

This repository contains results of an attempt of creating couple of models (via transfer-learning on the basis of
ESM-1b model https://github.com/facebookresearch/esm) to distinguish potential antimicrobial peptides from those which are not.

Fine-tuning was done via implementing MLP (multilayer perceptron) and Light Attenintion (https://github.com/HannesStark/protein-localization) based model which receives 
a hidden representation from the pre-trained BERT-like model as input. 

Both models (MLP-based ans LA-based) were trained in google colab, the code itself represents python notebooks 
and is located  a ipynb files. 

Source data files are localed in the data folder. 
