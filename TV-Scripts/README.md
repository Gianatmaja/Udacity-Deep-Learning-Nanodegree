# Project 3: Generate TV Scripts
In this project, we will be generating TV scripts using an RNN model. To do this, we'll be using a TV script dataset from 9 seasons of Seinfeld. We'll be loading and preprocessing this data, before using it to train the RNN that we defined. In the end, we'll be using the trained network to generate fake TV scripts.

### Project Structure
This repository has the following structure

    .
    ├── images                                    # Contains images used in README
    ├── data                                      # Seinfeld TV Scipts data
    ├── dlnd_tv_script_generation.ipynb           # Main notebook
    ├── generated_script_1.txt                    # Results
    ├── helper.py                                 # Helper functions
    ├── problem_unittests.py                      # Unit testing function
    └── README.md

The bulk of the codes are implemented in the dlind_tv_script_generation.ipynb file, with some helper functions defined separately in helper.py (for preprocessing data, loading, saving model, etc.) and problem_unittests.py. The data used for training is the Seinfeld TV scripts data for 9 seasons, which is stored in the data folder, and the results of the RNN-generated script can be seen in the generated_script_1.txt file.

### Results
Some screenshots of the results obtained during the project can be seen below.
![res](https://github.com/Gianatmaja/Udacity-Deep-Learning-Nanodegree/blob/main/TV-Scripts/images/Screenshot%202022-10-14%20at%2010.07.13%20PM.png)
