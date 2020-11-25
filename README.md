# Link to Google Doc project.
https://docs.google.com/document/d/1Kb_J5WfAwnJBapz6ZQFczAWgAVzlgKiWKP9tk-ZRwig/edit?usp=sharing


## Deep Neural Networks for Drugs Classification Based on Biological Activity

[1] S. Popov, A. Babenko, S. Morozov - Neural Oblivious Decision Ensembles for Deep Learning on Tabular Data. arxiv/1909.06312

[2] Mechanisms of Action (MoA) Prediction - kaggle.com/c/lish-moa

# Folders structure

There's currently 2 models available.

## DNN
`notebooks/MoA_DNN.ipynb`

```
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
flatten_8 (Flatten)          (None, 876)               0         
_________________________________________________________________
dense_32 (Dense)             (None, 480)               420960    
_________________________________________________________________
dense_33 (Dense)             (None, 480)               230880    
_________________________________________________________________
dense_34 (Dense)             (None, 480)               230880    
_________________________________________________________________
dense_35 (Dense)             (None, 480)               230880    
_________________________________________________________________
last_frozen (Dense)          (None, 480)               230880    
_________________________________________________________________
dense_36 (Dense)             (None, 206)               99086     
_________________________________________________________________
dense_37 (Dense)             (None, 206)               42642     
=================================================================
Total params: 1,486,208
Trainable params: 1,486,208
Non-trainable params: 0
```

## NODE
`notebooks/MoA_NODE.ipynb`

```
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
lambda (Lambda)              multiple                  0         
_________________________________________________________________
batch_normalization (BatchNo multiple                  3140      
_________________________________________________________________
batch_normalization_1 (Batch multiple                  3652      
_________________________________________________________________
batch_normalization_2 (Batch multiple                  4164      
_________________________________________________________________
batch_normalization_3 (Batch multiple                  4676      
_________________________________________________________________
dropout (Dropout)            multiple                  0         
_________________________________________________________________
dropout_1 (Dropout)          multiple                  0         
_________________________________________________________________
dropout_2 (Dropout)          multiple                  0         
_________________________________________________________________
dropout_3 (Dropout)          multiple                  0         
_________________________________________________________________
odst (ODST)                  multiple                  39510     
_________________________________________________________________
odst_1 (ODST)                multiple                  41814     
_________________________________________________________________
odst_2 (ODST)                multiple                  44118     
_________________________________________________________________
dense (Dense)                multiple                  241020    
=================================================================
Total params: 382,094
Trainable params: 371,974
Non-trainable params: 10,120
```
