# NLP_reviews
********
Simon Yang, September 2021
********

### Predicting Amazon review rating 
This repository contains code and documentation to: _train and test a model predicting the “Overall” Amazon reviews' rating__. 

### Notebooks
- NLP_reviews.ipyb: main Jupyter notebook containing the code to train a model to predict ratings from text reviews.
- NLP_reviews_summary.ipyb: documentation Jupyter notebook detailing the approach and steps used tune and train a model that predicts ratings from text reviews.

### Requirements
1. The requirements to run NLP_reviews.ipyb can be found in env.yml. Use conda to install:

  `conda env create -f env.yml`

  `conda activate NLP_reviews`

2. Download the review data and unzip to /data/:

  `cd data/`

  `wget http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Apps_for_Android_5.json.gz`

  `gzip -d reviews_Apps_for_Android_5.json.gz`

### Directories
The directories are here for order: 
-/data/ -- should contain reviews_Apps_for_Android_5.json. See above for how to download the review data.
- /models/ -- NLP_reviews.ipyb saves instances of trained models to this directory
- /img/ -- NLP_reviews.ipyb saves confusion matrixc plots to this directory

