# Deep Text Classifier

Implementation of document classification model described in [Hierarchical Attention Networks for Document Classification (Yang et al., 2016)](https://www.cs.cmu.edu/~diyiy/docs/naacl16.pdf).

## How to run
Get Yelp review dataset here: https://www.yelp.com/dataset_challenge
```
python3 yelp_prepare.py yelp_academic_dataset_review.json
python3 worker.py yelp train
```
