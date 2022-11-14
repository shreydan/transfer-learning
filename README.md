# **Transfer Learning Projects**

- `Flower-Classification` : [Kaggle Notebook](https://www.kaggle.com/shreydan/resnet50-pytorch-lightning-kfolds)
  - Model: ResNext50 -- fine tuning
  - Fully-Connected: in_features->128, 0.3 Dropout, 128->16
  - Epochs: 5
  - 4 Stratified KFolds
  - 92.80% Validation Accuracy and 92.75% Test Accuracy in Fold 2

- `Pawpularity Contest` : [Kaggle Notebook](https://www.kaggle.com/code/shreydan/convnext-tiny-lightning-timm)
  - Model: ConvNext-Tiny -- finetuning
  - Merging logits and tabular data
  - Early Stopping
  - Albumentations package
