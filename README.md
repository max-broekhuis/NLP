# NLP
## NLP Projects
In this NLP Project I used a dataset of French search term browser history and applied machine learning methods to predict age 
and classify gender. The dataset contains over 6M rows
The first step involved transforming the series into permutable strings and allocate their frequency. This returned a dataset 
of text that could be used to train CountVectoriser function from the nltk package. After this the TF-IDF function needed to be
trained. Finally it was time to build pipelines that incorporated the pre-processing transformation, the CountVectoriser,
the TF-IDF transformer, and the Machine Learning method. I built pipelines for the NaiveBayes, Random Forest, SVM, 
and Linear Regression (more for practice than anything since this model isn't very applicable in this case). The best performing
model was the Random Forest. 
