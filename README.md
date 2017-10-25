# UCLA Astronomy Machine Learning Reading group - Fall 2017

## Goals
Machine learning is a topic that has risen in prominence recently as we get more and more data. We are seeing techniques from machine learning used more widely in astronomy. The goal of this reading group is to become more familiar with topics in machine learning and its connections to statistical tools that are in use in Astronomy. The plan is to go through a couple of textbooks on machine learning and discuss the basic underlying principles and methods. It would be in the style of a reading group where everyone would read the same topic, but a presenter would rotate each meeting and present a topic with associated code implementing the algorithm.

## Readings
- Fundamentals of Machine Learning for Predictive Data Analytics - Kelleher, J.; Namee, B.; D'Arcy, A.
- Deep Learning by Goodfellow, I.; Bengio, Y.;  Courville, A.
  - website: http://www.deeplearningbook.org/
  - https://github.com/HFTrader/DeepLearningBook
- Python Data Science Handbook by VanderPlas, J.
  - website: https://github.com/jakevdp/PythonDataScienceHandbook
- Hands-On Machine Learning with Scikit-Learn and TensorFlow
  - Safari Books Online: http://proquest.safaribooksonline.com/book/programming/9781491962282
  - github page: https://github.com/ageron/handson-ml
- Machine Learning: A Probabilistic Prespective - Kevin P. Murphy
- Data Analysis: A Bayesian Tutorial - Sivia, D. & Skilling, J. - Not part of regular reading, but this is a useful reference for Bayesian statistics

## Quick-Getting started with SciServer Compute
SciServer.org is a computational cloud environment that Johns Hopkins University (IDIES group) has generously allowed us to use for our projects. Jupyter notebooks/terminal are the interfaces to access datasets such as SDSS. Here's how to clone this github repo into your SciServer account:
1. Create an account at sciserver.org and go to Compute
2. Create a new container (Docker container), choose the type to be Python, and a container Jupyter notebook interface will be created.
3. On the right hand side, go to New-> terminal and a black terminal interface will appear.
4. In this order in the terminal, type each of these at a time (separated by a comma) and hit enter:
5. ls, cd home, ls, cd idies, cd workspace, cd persistent, ls, git clone url-of-git-repository-here
6. the respository will now be in your folder.


## Extra Readings
-Kirkpatrick, K. (2017). It's not the algorithm, it's the data. <i>Communications of the ACM</i>, 60(2), 21-23. https://doi.org/10.1145/3022181

## Code Samples
-- SciServer cosmology and astronomy Jupyter Notebook code samples https://github.com/sciserver/Notebooks


## Topics
Potential topics this quarter:
- clustering
- unsupervised learning
- Bayesian nets
- introduction to deep learning
- convolution neural networks


## Schedule
Meetings will take place on Fridays at 11 am to Noon in **PAB-3-703**. Room changes will be sent via email.

**Organizers**: Tuan Do ([@followthesheep](https://github.com/followthesheep)), Bernie Randles ([@brandles](https://github.com/brandles))

| Date | Topic | Readings | Presenter |
| --- | --- | --- | --- |
|2017-10-06 | Clustering  | VanderPlas Ch. 5 -  [K-Means Clustering](https://github.com/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.11-K-Means.ipynb) | T. Do|
|2017-10-13 | Gaussian Mixture Modeling  - Location: 4-330 PAB | VadnerPlas Ch. 5 -  [Gaussian-Mixtures ](https://github.com/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.12-Gaussian-Mixtures.ipynb), Murphy Exercise 11.9 | T. Do|
|2017-10-17 | Neural Networks |deeplearningbook.com, stop at 6.2.2. For some hands-on coding, (http://choonsiong.com/public/books/Big%20Data/Data%20Science%20from%20Scratch.pdf) p. 213 |B. Boscoe |
|2017-10-27 | | | A. Hees |
|2017-11-03 | | |  |
|2017-11-17 | | | A. Gautam, D. Chu |
|2017-12-01 | | | |
|2017-12-08 | | | G. Witzel |
|2017-12-15 | | | B. Randles, I. Pasquetto|
