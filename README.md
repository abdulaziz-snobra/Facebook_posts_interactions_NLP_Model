# Facebook interaction predictor , with Data collector

## NN Model that predicts the Facbook posts interaction based on the text phrases & contetnt type (img,video,other)


This project is an made whie trying to understand consepts of (machine learning ,NN and NLP), It compines between data collection and building the model. The main goal of this project is to scrape
Facebook pages on a specific neich, collect facebook content(text,data content type) to create a dataset that fed into Deep Neural Network model that has an embeddign layer, the gpal of the model is 
to redict the rate of post interaction from (1 to 10) based on it's text.

The project is made followig these steps: 

* Collecting Posts url from a public facebook page.
* Iterate over these posts and collect related data.
* Feature engineering ( converting numerical likes and comments into rates 1->10)
* Building and training the Model.
  
