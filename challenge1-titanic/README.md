# Challenge-titanic
https://www.kaggle.com/c/titanic

# Goal
Get above 85% accuracy. 

### Phase 1

Write a notebok to explore the dataset, make plots that you think are insightsful, and write the insights in the notebook.

### Phase 2

Write a notebook to model the dataset and get 85% on the kaggle website.
* Rememeber to split your data to three parts and the begining - train, validation, test. Use the train and validation to optimise your model and use the test data only once.
* You can also replace the train\validation with [cross validation](https://www.openml.org/a/estimation-procedures/1)

### Technologies:
Build 6 solutions based on:
1. [pandas](https://pandas.pydata.org/), [sklearn](http://scikit-learn.org/), [sklearn-pandas](sklearn-pandas),
2. [xgboost](https://github.com/dmlc/xgboost) with pandas
3. [lightGBM](https://github.com/Microsoft/LightGBM) with pandas
4. [TensorFlow](https://www.tensorflow.org/) and [Keras](https://keras.io/)
5. [h2o](https://www.h2o.ai/) without pandas
6. [turicreate](https://github.com/apple/turicreate) without pandas


### Phase 3
Write a server to provide predictios.
The server should replay to the route `/predict`, and given an example with features, return if the example survived.
* You are welcome to provide a web interface as well if you want.


## Notes
* The idea is to write good code which theoretically could be used for future deployments. 
* This project is about training, not just results.  
* Work with branches, not on the master in Github. 
* Use Python, [Jupyter](http://jupyter.org/), and [Turi](https://github.com/apple/turicreate)
* Always start by splitting the data into three parts: *train*, *validations* and *test*. You can use the *test* dataset **only once!** to prevent overfitting.
* The example code already have issues in it - good luck!
* Try to commit every small change to github, instead of big uploads of a lot of code.
