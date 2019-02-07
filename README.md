<h1>Classification of Cats and Dogs</h1>
<h2>About Project:</h2>
<p>
  The project is about classifying images of cats and dogs. I have used pretrained model densenet121 which is trained on Imagenet dataset. 
  So, that model will be a good feature extractor and I am changing the classifier part to classify the images of cats and dogs. 
  After training for just one epoch the model gave and accuracy of over 98%. <br />
  To the same model to classify the images of cats and dogs, you don't need to train again. I have uploaded <b><i>checkpoint.pth</i></b> 
  file that contains, number of input, hidden and output nodes and also the state_dict. You build the same classifier and load the 
  state dict into the model and directly use that.
  <br />
  <img src="https://github.com/SurajChinna/Classifying-Cats-and-Dogs/blob/master/assets/image1.png" />
</p>

<h2>Languages or frameworks used</h2>
<p>
<ul>
  <li>Python: language</li>
  <li>NumPy: library for numerical calculations</li>
  <li>Matplotlib: library for data visualisation</li>
  <li>Pytorch: a deep learning framework by Facebook AI Research Team for building neural networks</li>
  <li>torchvision: package consists of popular datasets, model architectures, and common image transformations for computer vision</li>
</ul>
</p>
