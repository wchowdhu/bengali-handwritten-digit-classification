# Bengali Handwritten Digit Classification

The goal of this project is to implement a machine learning model which takes as input an image of a Bengali handwritten digit and outputs the corresponding digit number from the 10 output classes.


## Install

The project requires latest Python version and the following libraries installed:   
  - [numpy](https://numpy.org/)
  - [pandas](https://pandas.pydata.org/)
  - [scikit-learn](https://scikit-learn.org/stable/)
  - [matplotlib](https://matplotlib.org/)
  - transformers
  - torch
  - glob
  - os
  - sys
  - random
  - cv2
  - tqdm


## Data

The dataset used for this project can be accesssed from [here](https://www.kaggle.com/datasets/wchowdhu/bengali-digits).

The dataset is structured into 10 folders, each folder contains images of Bengali digits for the corresponding number, e.g. `0` folder contains scanned images of Bengali digit `০`.
    0 --> ০
    1 --> ১
    2 --> ২
    3 --> ৩
    4 --> ৪
    5 --> ৫
    6 --> ৬
    7 --> ৭
    8 --> ৮
    9 --> ৯


## Code

The provided Jupyter notebook contains code covering exploratory data analysis, modeling, training, and evaluating model performance.


## Run

All codes were run on Kaggle kernel with a GPU.

To open the .ipynb files in your browser and look at the output of the completed cells, use the following command in your terminal after changing the working directory to the project directory `bengali-handwritten-digit-classification`:
```
jupyter notebook <file_name>.ipynb
```
