# Project 5: Deploying a Sentiment Analysis Model
In this project, we will be training a neural network to perform sentiment analysis on movie reviews. Then, we'll deploy the trained model on an AWS instance. We'll also use AWS Lambda and API Gateway so that the model is accessible from a web app. For this project, we'll be using the [IMDB Dataset](http://ai.stanford.edu/~amaas/data/sentiment/).

### Project Structure
This repository has the following structure

    .
    ├── images                    # Contains images used in README
    ├── serve                     # Contains codes to serve the model
    │  ├── model.py
    │  ├── predict.py
    │  ├── utils.py
    ├── train                     # contains codes to train the model
    │  ├── model.py
    │  ├── train.py
    ├── website                   # HTML file
    ├── SageMaker Project.ipynb   # Main notebook
    ├── report.html               # Notebook in html format
    └── README.md

The bulk of the codes are implemented on the SageMaker Project.ipynb notebook, with helper functions defined in .py files in the serve and train folder. The website folder contains a .html file for the web app, whereas report.html is a .html version of the SageMaker Project.ipynb notebook.
