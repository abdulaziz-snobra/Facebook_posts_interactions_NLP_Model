# Facebook interaction predictor , with Data collector

## NN Model that predicts the Facbook posts interaction based on the text phrases & contetnt type (img,video,other)


This project is an made whie trying to understand consepts of (machine learning ,NN and NLP), It compines between data collection and building the model. The main goal of this project is to scrape
Facebook pages on a specific neich, collect facebook content(text,data content type) to create a dataset that fed into Deep Neural Network model that has an embeddign layer, the gpal of the model is 
to redict the rate of post interaction from (1 to 10) based on it's text.

The project is made followig these steps: 

* Collecting Posts url from a public facebook page.
* Iterate over these posts and collect related data.
* Feature engineering ( converting numerical likes and comments into rates 1->10)
* Building and training the Model. ' Yet to come'

  
  
## How to make use of this project
As mentiond before this project is for training purposes, The code is not clean and has a lot of cells that are just for testing, but it has alot of documentation. so, it will not be too hard to read and understand. The following steps is are the Keys to understand and make a use of this project:

* [a  relative link](https://github.com/abdulaziz-snobra/Facebook_posts_interactions_NLP_Model/blob/main/Posts_links.ipynb) Is the first thing to do, this code you could useit to collect posts URLs. Using facebook page url, and number of scrolls you will find evrything works easy.
  **_NOTE:_**  To scrape page posts, the scaper scrolls down the page and collects URLs. So, increasing number of scrolls increasing posts URLs.
