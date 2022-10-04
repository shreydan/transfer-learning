# **Transfer Learning Projects**

- `Flower-Classification` : [Kaggle Notebook](https://www.kaggle.com/shreydan/resnet50-pytorch-lightning-kfolds)
  - Model: ResNext50 -- fine tuning
  - Fully-Connected: in_features->512, 0.5 Dropout, 512->16
  - Epochs: 5
  - 5 Stratified KFolds
  - 86% Validation Accuracy and 61% Test Accuracy in Fold 3

- `Pawpularity Contest` : [Kaggle Notebook](https://www.kaggle.com/code/shreydan/convnext-tiny-lightning-timm)
  - Model: ConvNext-Tiny -- finetuning
  - Merging logits and tabular data
  - Early Stopping
  - Albumentations package
