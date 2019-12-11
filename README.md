# Project Title

The following project, presented as a collection of JuPyteR notebooks, is titled "Machine Learning and Artificial Intelligence for Application in Cardiovascular Biomechanics" and produced as a final product in the course "KT8315 - PhD Seminar i konstruksjonsteknikk og material" at NTNU (The Norwegian University of Science and technology). The project presents an introduction to neural networks and how to apply them to mathematical models. Then the notebooks moves on to introduce more advanced networks, which are also applied to similar cardiovascular models and problems. Finally, the notebook moves away from neural networks and introduce a few other machine learning techniques which also have applications within cardiovascular biomechanics. 

All examples are using either tensorflow or keras. Other open source libraries for creating neural networks also exist, as an example [scikit-learn](https://scikit-learn.org/stable/modules/neural_networks_supervised.html) provides one of them, and you are encouraged to seek this out if you are further interested in avilable tools for performing machine learning. Scikit is also used here for scaling and other functionality.

The project is assembled by both self written code and from examples found on the web and further adapted to our own examples. All sources are referenced.

TABLE OF CONTENTS

* Chapter 1: Neural networks
	- Chapter 1.1 Basics of neural networks
	- Chapter 1.2 Other
	- Chapter 1.3 Physically Informed Neural Networks
	- Chapter 1.4 Recurrent Neural Networks
* Chapter 2: Other Machine Learning Methods
	- Chapter 2.1: Support Vector Machines
	- Chapter 2.2: Principal Component Analysis

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

The notebooks are written in Python 3, and requires both jupyter notebook and the following libraries for operation:

```
numpy
tensorflow ver. 1.13.1
matplotlib
jupyter
scikit-learn
keras
pyDOE
sympy
joblib
scipy
```

The .yml-file "CardiovascularML.yml" contains the necessary libraries. You can build this environment using for example [Anaconda](https://www.anaconda.com/)

```Tensorflow``` version 2 was released after the material in these notebooks were created, and _is not backwards compatible_ with the current notebooks, so please keep this in mind.


### Installing

The prerequisites are prepared in the CardiovascularML.yml file, which can set up a working enviroment using different tools. We recommend using Anaconda which has both Python 3 and jupyter notebook preinstalled.

```
conda env create -f CardiovascularML.yml
conda activate CardiovascularML
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Jupyter](https://jupyter.org/) - Provider of the notebook interface
* [Tensorflow](https://www.tensorflow.org/) - Library for constructing neural networks
* [Keras](https://keras.io/) - High level API for constructing neural networks

## Contributing

If you would like to contribute to the project, please contact

fredrik.e.fossan@ntnu.no

or

nikolai.l.bjordalsbakke@ntnu.no


## Authors

* **Fredrik E. Fossan** - Main author on stenosis examples, keras applications and Recurrent Neural Networks - [GitHub Profile](https://github.com/Fredf10)
* **Nikolai L. Bjørdalsbakke** - Main author on Windkessel examples, Support Vector Machine applications and Basics of Neural Networks - [GitHub Profile](https://github.com/Nikobjo)
* **Jacob T. Sturdy*** - Main author on Principal Component analysis example -

## Acknowledgments

* All contributors are mentioned, and the source for reused code and images are given in the notebooks. 

