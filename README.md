# Classification of Cats and Dogs
## About Project:

  The project is about classifying images of cats and dogs. I have used pretrained model densenet121 which is trained on Imagenet dataset. 
  So, that model will be a good feature extractor and I am changing the classifier part to classify the images of cats and dogs. 
  After training for just one epoch the model gave and accuracy of over 98%. <br />
  To the same model to classify the images of cats and dogs, you don't need to train again. I have uploaded <b><i>checkpoint.pth</i></b> 
  file that contains, number of input, hidden and output nodes and also the state_dict. You build the same classifier and load the 
  state dict into the model and directly use that.
  
  
  ![Output of Model](https://github.com/SurajChinna/Classifying-Cats-and-Dogs/blob/master/assets/image1.png "Output of Model")
  

## Languages or frameworks used 

  * Python: language
  * NumPy: library for numerical calculations
  * Matplotlib: library for data visualisation
  * Pytorch: a deep learning framework by Facebook AI Research Team for building neural networks
  * torchvision: package consists of popular datasets, model architectures, and common image transformations for computer vision
