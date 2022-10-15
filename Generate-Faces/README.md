# Project 4: Generate Faces
In this project, we will be using deep convolutional generative adversarial networks (DCGAN) to generate faces. We will be defining and training adversarial networks on the [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html). Then, we'll see how it performs by using is to generate fake sample faces.

### Project Structure
This repository has the following structure

    .
    ├── images                                    # Contains images used in README
    ├── dlnd_face_generation.ipynb                # Main notebook
    ├── train_samples.pkl                         # Generated faces
    ├── problem_unittests.py                      # Unit testing function
    └── README.md

The bulk of the codes are implemented in the dlind_face_generation.ipynb file, with some helper functions defined separately in problem_unittests.py. The generated faces obtained during the process is saved in the train_samples.pkl file.

Some screenshots of the training data used during the project can be seen below.
![train](https://github.com/Gianatmaja/Udacity-Deep-Learning-Nanodegree/blob/main/Generate-Faces/images/processed_face_data.png)

### Results
Some screenshots of the results obtained during the project can be seen below.
![res](https://github.com/Gianatmaja/Udacity-Deep-Learning-Nanodegree/blob/main/Generate-Faces/images/Screenshot%202022-10-15%20at%208.38.43%20AM.png)
