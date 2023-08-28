# Ant_Bee_Classification

![Ant_Bee](https://github.com/ufuksecilmis/Ant_Bee_Classification/assets/51096261/ba4840b1-5d9f-445f-98a0-51608c99afc5)
 
We will use Pytorch Lightning.

The problem we’re going to solve today is to train a model to classify ants and bees. We have about 120 training images each for ants and bees. There are 75 validation images for each class. This dataset is a very small subset of imagenet.

# Steps
1.Use torchvision to upload and transform images.

2.Create mini-batches for training.

3.Train ResNet-18 model from stratch

4.Test The Model

5.Create Confusion Matrix and ROC Curve

# Dataset

Download the data from here and extract it to the current directory.



# Model Results


![Conf_Mat](https://github.com/ufuksecilmis/Ant_Bee_Classification/assets/51096261/1a488d7f-8a0b-4e14-93c6-af4d77e801b3)
![Classification Report](https://github.com/ufuksecilmis/Ant_Bee_Classification/assets/51096261/5332b735-16b6-49ff-bb0a-b462d53a1ca3)
![ROC](https://github.com/ufuksecilmis/Ant_Bee_Classification/assets/51096261/9e14f594-8ab0-42d7-add8-6b4b1bec8941)
