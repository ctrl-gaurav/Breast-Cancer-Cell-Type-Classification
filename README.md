[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/ctrl-gaurav/Breast-Cancer-Cell-Type-Classification">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Breast Cancer Prediction and Classification</h3>

  <p align="center">
    A Machine Learning as well as Neural Network approach to solve classification problem.
    <br />
    <a href="https://github.com/ctrl-gaurav/Breast-Cancer-Cell-Type-Classification"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/ctrl-gaurav/Breast-Cancer-Cell-Type-Classification">View Demo</a>
    ·
    <a href="https://github.com/ctrl-gaurav/Breast-Cancer-Cell-Type-Classification/issues">Report Bug</a>
    ·
    <a href="https://github.com/ctrl-gaurav/Breast-Cancer-Cell-Type-Classification/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

The aim of this project is to select appropriate feature to train model and find out which classification algorithm work best for the given dataset.
This dataset of cancer cells characteristics was created by the University of Wisconsin. The features from the data set describe characteristics of the cell nuclei and are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.
The dataset has 569 instances and 32 attributes out of which 5 attributes are chosen for model : 
Mean Radius
Mean Perimeter
Mean Area
Mean Concavity
Mean Concave Points
The Objective is to train a classifier model to predict whether the cell is malignant or benign.

For this the Machine Learning models used were:

1. Logistic Regression
2. K-Nearest Neighbors(KNN)
3. Naïve Bayesian Algorithm

Results obtained were:

* Logistic Regression :
Accuracy: 92.98%
Cross validation score: 90.87% (+/- 5.91%)

* K-Nearest Neighbors (KNN):
Accuracy: 92.11%
Cross validation score: 88.23% (+/- 7.06%)

* Naive Bayes :
Accuracy: 94.74%
Cross validation score: 90.87% (+/- 5.91%)

Out of all Naive Bayes worked best for this particular data set.

Further when this was implemented by Simple Neural Network the results obtained were :

Accuracy: 87.72%
Loss: 0.4984

And to improve this, when dense neural network with some regularization techniques were used the results improved to:

Accuracy: 90.35%
Loss: 0.2877

### Built With

* [Keras](https://keras.io/)
* [Tensorflow](https://www.tensorflow.org/)
* [scikit-learn](https://scikit-learn.org/stable/)
