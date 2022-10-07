# Welcome to John Muller's Github.io page

For now I am using this to point to a few  of my github repos that have some ML/Data Science projects
that hopefully show a variety of skills.

I hope to keep adding to these with things like: more deep learning, NLP, and much more.

For now I will list 3 recent projects.

## Recent Data Science projects


### Comparison of Classification Methods.
The data is on stroke patients and from Kaggle and has attributes
  and an outcome variable of stroke or not.
In the project I am interested in how 3 models compare in accuracy:
     logistic regression, Gradient Boosting and Random Forests.  
The project also gave me a chance to use some hyper parameter tuning in sklearn.  
To see the code, open the notebook ***stroke.ipynb***  
from the repo https://github.com/jhmuller/stroke/

### Simple Image Classification.   
 I use tensorflow and Keras to try to distinguish
between 2 kids of flowers. While a fairly simple task, it's not my first image classification project,  but one of the first where I tried a lot of tuning.  
 I did manual tuning of the hyper parameters such as layers, dropout and learning rate.   
It's clear I am going to have to start using tools like Keras tune or some equivalent in PyTorch.   
To see the code, open the notebook ***flowers.ipynb***   
 from the repo https://github.com/jhmuller/flowers/

### Time Series Exploratory data analysys.
This is on energy price data from the Texas energy grid ERCOT.  
I had done time series EDA and some modeling with R,
but this gave me a chance to try doing the same with Python tools.  
To see the code, open the notebook ***timeseries.ipynb***
 from the repo https://github.com/jhmuller/timeseries

### Text Classification.
This is another Kaggle data set although originally from Reddit.
It is posts labeled as depression related or not.
I modeled my solution after some code from a Coursera class that uses tensorflow.  

To see the code, open the notebook ***text_classify.ipynb***  
  from the repo  https://github.com/jhmuller/text_classify

### Embeddings for recommendations.
In this project I use a movie rating dataset and derive embedddings
 for users and movies that can be used to derive a predicted
 rating of the movie by the user.  To get the prediction we take
 the dot product of the movie and user embeddings.

 The embeddings are "learnged" by training a neural network using Pytorch.

 Note that there are many more sophisticated ways to do recommentations including
   the Two Tower Model and now TorchRec.  However, this fairly simple Method
   seemed like a good place to start.

 To see the code, open the notebook ***recs.ipynb***  
  from the repo https://github.com/jhmuller/recs

## Contact Me
If you have questions about any of the projects or just want to contact me  
reach out to jmuller.ics88@gtalumni.org

Thank you.
