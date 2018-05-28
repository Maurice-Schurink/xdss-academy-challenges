# Challenge-titanic
This repository is for training future data-scientists in "industry-like" environment. 

## Instructions
1. Fork this repository. 
2. Read about the challenge and download the data.
3. Write code to solve the problem.
* Use branches (don't work on the GitHub master branch)
4. Export the notebook to python script and push the notebooks and python script to GitHub.
5. When having good results, create a pull request.
6. I will comment on the changes.
7. We reiterate with the comments until we're good to move forward to the next challenge. 

## Challenge
https://www.kaggle.com/c/titanic
Get above 85% accuracy. 

### Phase 1

Write a notebok to explore the dataset, make plots that you think is insightsful.

### Phase 2

Write a notebook to model the dataset and get 85% on the kaggle website.

### Phase 3
write a server to provide predictios.
the server should replay to the route `/predict`, and given an example, return if the example survived.


## Notes
* The idea is to write good code which theoretically could be used for future deployments. 
* This project is about training, not just results.  
* Work with branches, not on the master in Github. 
* Use Python, [Jupyter](http://jupyter.org/), and [Turi](https://github.com/apple/turicreate)
* Always start by splitting the data into three parts: *train*, *validations* and *test*. You can use the *test* dataset **only once!** to prevent overfitting.
* The example code already have issues in it - good luck!
* Try to commit every small change to github, instead of big uploads of a lot of code.
