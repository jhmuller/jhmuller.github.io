# Welcome to John Muller's Github.io page

Click [here](https://html-preview.github.io/?url=https://github.com/jhmuller/jhmuller.github.io/blob/main///index.html) for a nicer HTML version.

I am using this site to list pointers to a few  of my github repos
that have some ML/Data Science projects that hopefully show a variety of skills.

I use Jupyter notebooks for all of the projects.  I realize that in production
you are more likely to use Python scripts.  In fact, my style of development
is often to use both, migrating mature code
from a Notebook to functions and classes in a Python script.
However, the Notebooks offers the wonderful ability to embed
markdown with the code and I think that is a great asset for what
I am trying to achieve here.

## Sample of Data Science projects


-  **Comparison of Classification Methods**  
 The data is from Kaggle and on stroke patients.
 It has attributes and an outcome variable of stroke or not.
 In the project I am interested in how 3 models compare in accuracy:
     logistic regression, Gradient Boosting and Random Forests.  
The project also gave me a chance to use some hyper parameter tuning in sklearn.  
 The code and output can be found here  https://github.com/jhmuller/stroke/blob/main/stroke.ipynb

-  **Image Classification**   
 I use tensorflow and Keras to try to distinguish between 2 kids of flowers.
 While a fairly simple task, it's not my first image
 classification project,  but one of the first where I tried a lot of tuning.
 I did manual tuning of the hyper parameters such as layers, dropout and learning rate.
It's clear I am going to have to start using tools like Keras tune or
something equivalent in PyTorch.   
The code and output can be found here 
  https://github.com/jhmuller/flowers/blob/master/flowers.ipynb

-  **Using a PreTrained model for image classification**  
My NN for the image classification in the Simple Image Classification above
was very simple,  only 2 convolution and pooling layers.
Modern nets for image applications can have hundreds of layers,
so I wanted to retry the classification using the tensorflow
model MobileNet as a base model and retrain only the final
prediction layer. 
The code and output can be found here 
  https://github.com/jhmuller/pretrain/blob/main/pretrain.ipynb


-  **Text Classification**  
This is another Kaggle data set although originally from Reddit.
It is posts labeled as "depression related" or not.
I modeled my solution after some code from a Coursera class that uses tensorflow.  
The code and ouptupt can be found here 
  https://github.com/jhmuller/text_classify/blob/master/text_classify.ipynb

-  **Embeddings for recommendations**  
In this project I use a movie rating dataset and derive embedddings
 for users and movies that can be used to derive a predicted
 rating of the movie by the user.  To get the prediction we take
 the dot product of the movie and user embeddings.
 The embeddings are "learned" by training a neural network using Pytorch.
 Note that there are many more sophisticated ways to do recommendations including
   the Two Tower Model and now TorchRec.  However, this fairly simple Method
   seemed like a good place to start.  
The code and output can be found here   https://github.com/jhmuller/recs/blob/master/recs.ipynb

-  **Text generation**  
Chat bots and translation are a few examples of applications
of generating new text from some seed or starter text.
You can even play around with using it on your own starter
text at the Hugging Face website.
I wanted to get started with some of the Hugging face APIs AND I was
curious about text generation so I devised an experiment.
In particular, I was curious what would get generated if the   
seed were for example: famous book beginnings, movie quotes, jokes,
and other oddball starter strings.  
So I created a Jupyter notebook to try it out.  
The code and output can be found here https://github.com/jhmuller/text_gen/blob/master/text_gen.ipynb


-  **Clustering time series.**  
I found some interesting time series data on electricity cost
at the state/month level.  Too coarse for energy trading
but maybe useful to understand macro trends in prices.
I used Kmeans to cluster the series.  The resulting
clusters were interesting and I think I could tell a story
for most of the results.
The code and output can be found here
https://html-preview.github.io?url=https://github.com/jhmuller/energy_price/blob/main/energy_clusters.html   
======================================================

## Contact Me
If you have questions about any of the projects or just want to contact me  
reach out to jmuller.ics88@gtalumni.org

Thank you.
