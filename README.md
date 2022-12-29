# Welcome to John Muller's Github.io page

I am using this site to list pointers to a few  of my github repos
that have some ML/Data Science projects that hopefully show a variety of skills.

I use Jupyter notebooks for all of them.  I realize that in production
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
 To see the code, open the notebook ***stroke.ipynb***  
from the repo https://github.com/jhmuller/stroke/

-  **Image Classification**   
 I use tensorflow and Keras to try to distinguish between 2 kids of flowers.
 While a fairly simple task, it's not my first image
 classification project,  but one of the first where I tried a lot of tuning.
 I did manual tuning of the hyper parameters such as layers, dropout and learning rate.
It's clear I am going to have to start using tools like Keras tune or
something equivalent in PyTorch.   
To see the code, open the notebook ***flowers.ipynb***   
 from the repo https://github.com/jhmuller/flowers/

-  *Using a PreTrained model for image classification**  
My NN for the image classification in the Simple Image Classification above
was very simple,  only 2 convolution and pooling layers.
Modern nets for image applications can have hundreds of layers,
so I wanted to retry the classification using the tensorflow
model MobileNet as a base model and retrain only the final
prediction layer.  
To see the code, open the notebook ***pretrain.ipynb***   
 from the repo https://github.com/jhmuller/pretrain/


-  **Time Series Exploratory data analysis**  
This is on energy price data from the Texas energy grid ERCOT.
I had done time series EDA and some modeling with R,
but this gave me a chance to try doing the same with Python tools.  
To see the code, open the notebook ***timeseries.ipynb***  
 from the repo https://github.com/jhmuller/timeseries

-  **Text Classification**  
This is another Kaggle data set although originally from Reddit.
It is posts labeled as "depression related" or not.
I modeled my solution after some code from a Coursera class that uses tensorflow.  
To see the code, open the notebook ***text_classify.ipynb***  
  from the repo  https://github.com/jhmuller/text_classify

-  **Embeddings for recommendations**  
In this project I use a movie rating dataset and derive embedddings
 for users and movies that can be used to derive a predicted
 rating of the movie by the user.  To get the prediction we take
 the dot product of the movie and user embeddings.
 The embeddings are "learned" by training a neural network using Pytorch.
 Note that there are many more sophisticated ways to do recommendations including
   the Two Tower Model and now TorchRec.  However, this fairly simple Method
   seemed like a good place to start.  
 To see the code, open the notebook ***recs.ipynb***  
  from the repo https://github.com/jhmuller/recs

-  **Text generation**  
Chat bots and translation are a few examples of applications
of generating new text from some seed or starter text.
You can even play around with using it on your own starter
text at the Hugging Face website.
I wanted to get started with some of the Hugging face APIs AND I was
curious about text generation so I devised an experiment.
In particular, I was curious what would get generated if the   
seed were for example
* famous book beginnings,
* movie quotes
* jokes, and other oddball starter strings.  
So I created a Jupyter notebook to try it out.  
To see the code, open the notebook ***text_gen.ipynb***  
 from the repo https://github.com/jhmuller/text_gen


-  **Predicting Churn**  
I wanted to try using a notebook in the AWS Sagemaker environment
and also try out some Sagemaker functionality.
I found an example on the AWS site so I first tried to reproduce it.
That did not quit work so I pivoted and finished the modeling part
of the project with Sklearn.
I will continue to experiment with AWS Sagemaker's notebook functionality
and perhaps soon find it as easy to use as Colab.  
To see the code, open the notebook ***churn.ipynb***  
 from the repo https://github.com/jhmuller/sage_churn


- **Predicting the next word**  
Watching how well the text app on my phone can guess the next word,
I decided to try to build a model to do the same thing.
I found an article about doing this which I used as a template
but I changed some things from the article, especially about the data.
The model is built using Keras/tensorflow.  
To see the code, open the notebook ***nextWord.ipynb***  
  from the repo https://github.com/jhmuller/nextWord

-  **Clustering time series.**  
I found some interesting time series data on electricity cost
at the state/month level.  Too coarse for energy trading
but maybe useful to understand macro trends in prices.
I used Kmeans to cluster the series.  The resulting
clusters were interesting and I think I could tell a story
for most of the results.
To see the code open the notebook ***energy_clusters.ipynb***  
  from the repo https://github.com/jhmuller/energy_price  
======================================================

## Contact Me
If you have questions about any of the projects or just want to contact me  
reach out to jmuller.ics88@gtalumni.org

Thank you.
