# NLP_reviews
********
Simon Yang, September 2021
********

### Predicting Amazon review rating 
This repository contains code and documentation to: __train and test a model that predicts the “Overall” Amazon reviews' rating__. 

*******
### Requirements
1. The requirements to run NLP_reviews.ipyb can be found in env.yml. Use conda to install the required libraries:

  `conda env create -f env.yml`

  `conda activate NLP_reviews`

2. Download the review data and unzip to /data/:

  `cd NLP_reviews/`
  
  `mkdir ./data; cd data`

  `wget http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Apps_for_Android_5.json.gz`

  `gzip -d reviews_Apps_for_Android_5.json.gz `
  
   `cd ..`

  
  
3. create required directories

`mkdir ./models`

`mkdir ./img`

`mkdir ./out`

**************
### Notebooks
- __NLP_reviews_summary.ipyb__: documentation Jupyter notebook detailing the approach and steps used tune and train a model that predicts ratings from text reviews.
- __NLP_reviews.ipyb__: main Jupyter notebook containing the code to train a model to predict ratings from text reviews.

### Notebooks in html format:
- __NLP_reviews_summary.html__
- __NLP_reviews.html__


### Directories
The directories are here for order: 
- __/data/__ -- should contain reviews_Apps_for_Android_5.json. See above for how to download the review data.
- __/models/__ -- NLP_reviews.ipyb saves instances of trained models to this directory
- __/img/__ -- NLP_reviews.ipyb saves confusion matrixc plots to this directory
- __/out/__ -- NLP_reviews.ipyb saves model parameters and output to this directory

***********
