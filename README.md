# ECE-GY-9163-Machine Learning for Cybersecurity Lab 4

Running the code:
To run the code, first download the models 'bd_net.h5' and 'bd_weights.h5' from this repository.
Then download the dataset from the link provided in the README of the folder 'Lab3' from the link 'https://github.com/csaw-hackml/CSAW-HackML-2020/tree/master'.
There would be 2 datasets in 'cl' folder with clean data (test.h5 , valid.h5) and 2 datasets in 'bd' folder with poisoned or bad data (bd_test.h5 , bd_valid.h5).
Save both the datasets and models in a single folder.

This is the architecture of the code we are going to run:

├── data 
    └── cl
        └── valid.h5 // this is clean validation data used to design the defense
        └── test.h5  // this is clean test data used to evaluate the BadNet
    └── bd
        └── bd_valid.h5 // this is sunglasses poisoned validation data
        └── bd_test.h5  // this is sunglasses poisoned test data
├── models
    └── bd_net.h5
    └── bd_weights.h5
├── architecture.py
└── eval.py // this is the evaluation script

Upload the folder on Jupyter and open the code 'MLCybersecLab4.ipynb' from this library if you are using Jupyter Notebook.

If you are using Google Colab, upload the models and datasets to your drive and then mount the drive to the colab notebook using the following code:

from google.colab import drive
drive.mount('/content/drive')

We are all set to run the whole code now on any environment.
