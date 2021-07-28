<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/ctrl-gaurav/Breast-Cancer-Cell-Type-Classification">
    <img src="images/logo.jpg" alt="Logo" width="576" height="324">
  </a>

  <h3 align="center">Breast Cancer Prediction and Classification</h3>

  <p align="center">
    A Machine Learning as well as Deep Learning approach to solve classification problem.
    <br />
    <a href="https://github.com/ctrl-gaurav/Breast-Cancer-Cell-Type-Classification/blob/main/README.md"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/ctrl-gaurav/Breast-Cancer-Cell-Type-Classification">View Demo</a>
    ·
    <a href="https://github.com/ctrl-gaurav/Breast-Cancer-Cell-Type-Classification/issues">Report Bug</a>
    ·
    <a href="https://github.com/ctrl-gaurav/Breast-Cancer-Cell-Type-Classification/issues">Request Feature</a>
  </p>
</p>



## Table of Contents

- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)
- [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Product Screenshots](#product-screenshots)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)



## About The Project


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


## Built With

* [Keras](https://keras.io/)
* [Tensorflow](https://www.tensorflow.org/)
* [scikit-learn](https://scikit-learn.org/stable/)


## Getting Started

To get a local copy up and running follow these simple example steps.


### Prerequisites

You will need:

- Python 
- Tensorflow 
- scikit-learn


### Installation

1. Make sure you have python3 setup on your system
2. Clone the repo
```sh
git clone https://github.com/ctrl-gaurav/Breast-Cancer-Cell-Type-Classification.git
```
3. Install requirements
```sh
pip install -r requirements.txt
```
4. Run script.py 
```sh
python script.py
```


## Roadmap

See the [open issues](https://github.com/ctrl-gaurav/Breast-Cancer-Cell-Type-Classification/issues) for a list of proposed features (and known issues).


## Contributing

To add your contributions to this project follow these steps :

1. Fork the Project
2. Create your improvements Branch (`git checkout -b improvements/myimprovements`)
3. Commit your Changes (`git commit -m 'Done some Improvements'`)
4. Push to the Branch (`git push origin improvements/myimprovements`)
5. Open a Pull Request


## License

Distributed under the MIT License. See `LICENSE` for more information.


## Contact

- Gaurav 
  - Insta Handle - [@ig_itsgk](https://www.instagram.com/ig_itsgk/) 
  - LinkedIn - [Gaurav](https://www.linkedin.com/in/gaurav-726239157/) <br />
- Project Link: [https://github.com/ctrl-gaurav/Breast-Cancer-Cell-Type-Classification](https://github.com/ctrl-gaurav/Breast-Cancer-Cell-Type-Classification)


