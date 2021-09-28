# NLP_reviews
# Simon Yang
# September 2021

# This repository contains code and documentation to address the following problem:
## __Build and present a model predicting the “Overall” Amazon reviews' rating__

# NLP_reviews.ipyb: main Jupyter notebook containing the code to train a model to predict ratings from text reviews.

# NLP_reviews_summary.ipyb: documentation Jupyter notebook detailing the approach and steps used tune and train a model that predicts ratings from text reviews.

# The requirements to run NLP_reviews.ipyb can be found in env.yml. Use conda to install:
## conda env create -f env.yml
## conda activate NLP_reviews

# The directories are here for order: 
-/data/ -- reviews_Apps_for_Android_5.json should be downloaded and unzipped to this directory. You can get download the data from: http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Apps_for_Android_5.json.gz
- /models/ -- running NLP_reviews.ipyb will save instances of the trained model to this directory
- /img/ -- running NLP_reviews.ipyb save confusion matrixc plots to this directory

