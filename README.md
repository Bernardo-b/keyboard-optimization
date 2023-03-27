# Keyboard Optimization

This project aims to optimize the layout of a keyboard to minimize distance travelled by fingers to type text.

## Project Overview

The project uses an optimization algorithm to find the optimal layout of keys on a keyboard based on a large dataset of common words and their frequency of use. The algorithm generates multiple generations of keyboard layouts and selects the best-performing ones to create the next generation.

The optimization process includes two main functions: `get_points()` and `mutation()`. The `get_points()` function calculates the score of a given keyboard layout based on the distance between each key and its neighboring keys. The `mutation()` function randomly mutates a keyboard layout to create new, potentially better layouts.

## Dataset

The dataset used for training the optimization algorithm comes from a [Brazilian Portuguese Sentiment Analysis Datasets](https://www.kaggle.com/datasets/fredericods/ptbr-sentiment-analysis-datasets?resource=download) from Kaggle and includes a large set of common words and their frequency of use in the Portuguese language. 

## Requirements

To run the project, you will need Python 3 and the following libraries:

- pandas
- numpy
- matplotlib
- tqdm

## Usage

To use the project, simply run the `keyboard_optimization.ipynb` Jupyter notebook. The notebook contains all the necessary code to generate and optimize a keyboard layout.

## Results

The optimized keyboard layout has a unique arrangement of keys that maximizes typing speed and minimizes finger movement. The layout tends to group frequently used keys in the center of the keyboard and less frequently used keys on the edges.
