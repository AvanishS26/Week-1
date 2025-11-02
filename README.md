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
