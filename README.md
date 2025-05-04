
# Mask Detection with PyTorch
This project will take in an image input and output the predicted label from the machine learning model.

I will also be implementing the TinyVGG model architecture.

Labels include:
- [Mask]
- [No_Mask]
- [Incorrect_Mask]

## TinyVGG Model Architecture
Model Architecture will be referenced from this site: https://poloclub.github.io/cnn-explainer/

## Dataset
In the repository the dataset has been split into test and train folders, each with the 3 respective class images and labels.

## Augmentation of Dataset
- I will be experimenting with 2 different transforms of the dataset one with `HorizontalFlip` and another with no augmentation.  

# Model Results

## Model 0 Loss and Accuracy Curve
![](https://github.com/TYW02/PyTorch_mask_detector/blob/master/images/model0_curve.png)


## Model 1 Loss and Accuracy Curve
![](https://github.com/TYW02/PyTorch_mask_detector/blob/master/images/model1_curve.png)

# Findings
Model 0 is currently overfitting
![](https://github.com/TYW02/PyTorch_mask_detector/blob/master/images/both_model_compare.png)



# Summary
Despite model 0 overfitting during the final test it seems like model 0 was able to predict the correct label while model 1 was not.

This difference in prediction could be due to the augmentation in dataset where model 0 was able to be more robust as compared to model 1. 




