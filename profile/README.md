# MOSAIKS:An Open Source Pipeline for Agricultural Remote Sensing in Zambia

## Purpose

This GitHub organization hosts the code and documentation for the MOSAIKS Capstone Project oft the Masters of Environmental Data Science program at the Bren School of Environmental Science and Management, University of California, Santa Barbara. This project intends to adapt, extend, and apply the MOSAIKS framework described in [Rolf et al. 2021](https://www.nature.com/articles/s41467-021-24638-z) to encode monthly imagery from the Landsat and Sentinel 2 satellite missions through random convolutional features over the years 2013 - 2021 and builds off the [Crop MOSAIKS Capstone Project](https://bren.ucsb.edu/projects/open-source-pipeline-remote-sensing-crop-yields-zambia-case-study) completed in 2022. The features are produced using an _unsupervised_ machine learning approach called random kitchen sinks. The resulting features are task-agnostic and therefore can be used to model a wide variety of tasks. The features are geolocated and can be geospatially joined to observed data for training purposes.

In this application of the MOSAIKS approach, the features are joined to agricultural data in  and multiple models are trained on this merged data using a _supervised_ machine learning approach, cross validated ridge regression. Our model is optimized for this specific task through systematically comparing model perfomance for various temporal subsetts including month and year range, spectral band combinations, spatially masking for cropland, several interpolation approaches, and weighted averages for features summarized to district levels. The optimized model is then applied to predict agricultural data geographic reagions where data is not present. This project is limited by data availability and is restricted to the country of Zambia.

## What is here?

This organization hosts four repositories including:
 1. [Preprocessing](https://github.com/mosaiks-capstone/Preprocessing)
 2. [Featurization](https://github.com/mosaiks-capstone/Featurization)
 3. [Modeling](https://github.com/mosaiks-capstone/Modeling)
 4. [Visualizations](https://github.com/mosaiks-capstone/Visualizations)

## Contributing

The capstone project's completion date is June 9th, 2023. Some team members will be continuing work in this field and the repositories may stay active for some time to come. Suggestions for improvements to the code or documentation are welcomed and encouraged. Please submit questions, comments, or code via issues or pull requests to the reposetories in this organisation. To correspond with the data scientists who produced these materials, please see their personal GitHub accounts listed below and feel free to contact them via email:

[Andrew Bartnik](https://github.com/andrewbartnik)\
[Carlo Broderick](https://github.com/CarloBroderick)\
[Gabrielle Smith](https://github.com/gabriellensmith)\
[Hailey Viers](https://github.com/hveirs)

## Acknowledgements

Much of the code and copy in this organization was supported by or originates from the 2022 University of California, Santa Barbara, Bren School of Environmental Science and Management, Master of Environmental Data Science Capstone: [CropMOSAIKS An Open-source Pipeline for Remote Sensing of Crop Yields: a Zambia Case Study](https://github.com/cropmosaiks)

Much thanks to them and to Cullen Molitor for their support. 
