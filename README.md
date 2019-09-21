# Tags_recommender
Developing a tag recommendation system for StackOverflow.

### 2 Parts:
- Filtering Tags and Text Pre-processing notebook
- Notebook of differerent recommendation systems using supervised (RFC & SVC) and unsupervised (LDA) algorithms

### Results:
- All the models are doing better than the dummy classifier (Jaccard score on test set: 0.009)
- Jaccard score of LDA model on test set is 0.04
- Jaccard score of Random Forest Classifier model on validation set is 0.14
- Jaccard score of OneVSRest (using Linear Support Vector Classifier) model on validation set is 0.28
- Jaccard score of OneVSRest (using Linear Support Vector Classifier) model on test set is 0.30
- The best model is OneVSRest using Linear SVC
