# Classification of Cats and Dogs
> Classifies whether an image is of a dog or cat based on the features

## Table of contents
* [About Project](#about-project)
* [Languages or Frameworks Used](#languages-or-frameworks-used)
* [Setup](#setup)

## About Project:

  The project is about classifying images of cats and dogs. I have used pretrained model densenet121 which is trained on Imagenet dataset. 
  So, that model will be a good feature extractor and I am changing the classifier part to classify the images of cats and dogs. 
  After training for just one epoch the model gave and accuracy of over 98%. <br />
  To the same model to classify the images of cats and dogs, you don't need to train again. I have uploaded <b><i>checkpoint.pth</i></b> 
  file that contains, number of input, hidden and output nodes and also the state_dict. You build the same classifier and load the 
  state dict into the model and directly use that.
  
  
  ![Output of Model](https://github.com/SurajChinna/Classifying-Cats-and-Dogs/blob/master/assets/image1.png "Output of Model")
  

## Languages or Frameworks Used 

  * Python: language
  * NumPy: library for numerical calculations
  * Matplotlib: library for data visualisation
  * Pytorch: a deep learning framework by Facebook AI Research Team for building neural networks
  * torchvision: package consists of popular datasets, model architectures, and common image transformations for computer vision
  
## Setup
  
  To use this project, clone the repo
  
  ### Clone
  ```
    git clone https://github.com/Surya-Prakash-Reddy/Classifying-Cats-and-Dogs.git
  ```
  
  After cloning, you can use the `Classifier.ipynb` notebook to learn or modify. You can also use `checkpoint.pth` file if you do not wish to train your model again or build some webapps using the model. If you are using `checkpoint.pth`, you can find the architecture in `Classifier.ipynb`
