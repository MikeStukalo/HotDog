# HotDog
Just a fun way to recreate Hotdog/Not Hotdog code from Silicone Valley using TensorFlow


# Data
The training set is taken from Kaggle [link](https://www.kaggle.com/datasets/dansbecker/hot-dog-not-hot-dog/)


# Description
'Hotdog Notebook.ipynb' trains a visual recognition model that can classify between HotDogs and NotHotDogs following the scene in Silicone Valley [link](https://youtu.be/ACmydtFDTGs?si=XSK1L9nGNLKS25QE)


First, I train a simple model that uses just the dataset. As expected, the accuracy is quite low due to very few examples used for training. 

Next, I use transfer learning and Imagenet pre-trained model. 

The results can be tested using .jpeg pictures. For start, there are a couple of pictures in example/ folder.

# Deployment
/deploy folder includes scripts to create a Sknowflake-based model and deploy it via a StreamLit App
