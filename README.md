# Week-1
# Project: Algae Bloom Detection in Water

This project is a Convolutional Neural Network (CNN) built to
classify images of water as either 'healthy_water' or 'algae_bloom'.

## Problem Statement
Traditional water quality monitoring is too slow and expensive to provide timely warnings for toxic Harmful Algal Blooms (HABs). This project will build a fast, low-cost Convolutional Neural Network (CNN) that instantly classifies a water photo as healthy-water or algae-bloom to serve as a rapid, accessible early-warning system.


The 'water_images/' is not included in this repository. To run this 
project, you must create your own dataset with the following 
structure:

water_dataset/
├── train/
│   ├── algae_bloom/
│   └── healthy_water/
└── test/
    ├── algae_bloom/
    └── healthy_water/

Week 2
## . Model Architecture

We built a simple, sequential CNN from scratch to learn the fundamentals of image classification.

The architecture is as follows:

1.  `Input` (150x150x3)
2.  `Conv2D` (32 filters, 3x3 kernel, ReLU)
3.  `MaxPooling2D` (2x2)
4.  `Conv2D` (64 filters, 3x3 kernel, ReLU)
5.  `MaxPooling2D` (2x2)
6.  `Conv2D` (128 filters, 3x3 kernel, ReLU)
7.  `MaxPooling2D` (2x2)
8.  `Flatten`
9.  `Dense` (128 units, ReLU)
10. `Dense` (1 unit, Sigmoid) - _Output Layer_

## . Current Status (End of Week 2)

* **Model:** The model has been successfully built and trained for 15 epochs.
* **Result:** The initial training run achieved a **validation accuracy of 93.33%**.
* **Next Steps (Week 3):** The training history shows signs of instability and overfitting, which will be the focus of our "Evaluation" and "Optimization" tasks next week.

## . How to Run

1.  Clone this repository.
2.  Prepare a dataset with the folder structure shown in section 2.
3.  Upload the `water_classification_model.ipynb` notebook to Google Colab.
4.  Upload your dataset (e.g., as `water_images.zip`) to the Colab environment and unzip it.
5.  Run all cells in the notebook in order.
   
