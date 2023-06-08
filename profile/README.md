# MOSAIKS: Open Source Pipeline for Agricultural Remote Sensing in Zambia

## Overview

This GitHub organization contains the code and documentation for the MOSAIKS Capstone Project of the Masters of Environmental Data Science program at the Bren School of Environmental Science and Management, University of California, Santa Barbara. This project aims to adapt, extend, and apply the MOSAIKS framework as described in [Rolf et al. 2021](https://www.nature.com/articles/s41467-021-24638-z) to encode monthly imagery from Landsat and Sentinel 2 satellite missions using random convolutional features from 2013 to 2021. The project builds upon the [Crop MOSAIKS Capstone Project](https://bren.ucsb.edu/projects/open-source-pipeline-remote-sensing-crop-yields-zambia-case-study) completed in 2022.

## Objective

The MOSAIKS approach uses an _unsupervised_ machine learning method called random kitchen sinks to produce task-agnostic features that can predict a wide range of variables. These geolocated features are joined to Zambian agricultural data, and multiple models are trained on this merged dataset using a _supervised_ machine learning method, cross-validated ridge regression. The models are optimized for their prediction tasks through systematic comparisons of model performance across temporal subsets, spectral band combinations, and interpolation approaches. The optimized models are then used to predict agricultural data for regions lacking data.

## Workflow

The repositories should be reviewed sequentially. If a user intends to repurpose this GitHub organization for their own project, they may be able to bypass much of the preprocessing repository, as it primarily focuses on processing ground truth training data specific to this project.

## Repositories

This organization hosts four repositories:

 1. [Preprocessing](https://github.com/mosaiks-capstone/Preprocessing)
 2. [Featurization](https://github.com/mosaiks-capstone/Featurization)
 3. [Modeling](https://github.com/mosaiks-capstone/Modeling)
 4. [Visualizations](https://github.com/mosaiks-capstone/Visualizations)

## Contributing

The capstone project's completion date is June 9th, 2023. Some team members will continue working in this field, and the repositories may remain active. Suggestions for improvements to the code or documentation are welcome and encouraged. Please submit questions, comments, or code via issues or pull requests to the repositories in this organization. To contact the data scientists who produced these materials, please see their personal GitHub accounts listed below and feel free to contact them via email:

[Andrew Bartnik](https://github.com/andrewbartnik)\
[Carlo Broderick](https://github.com/CarloBroderick)\
[Gabrielle Smith](https://github.com/gabriellensmith)\
[Hailey Viers](https://github.com/hveirs)

## Acknowledgements

Much of the code and documentation in this organization were supported by or originated from the 2022 University of California, Santa Barbara, Bren School of Environmental Science and Management, Master of Environmental Data Science Capstone: [CropMOSAIKS An Open-source Pipeline for Remote Sensing of Crop Yields: a Zambia Case Study](https://github.com/cropmosaiks)

Special thanks to them and to Cullen Molitor and Tamma Carleton for their support.

