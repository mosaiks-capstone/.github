# [MOSAIKS:](https://bren.ucsb.edu/projects/measuring-agricultural-adaptation-climate-change-zambia-using-satellite-imagery-and) Measuring Agricultural Adaptation to Climate Change in Zambia Using Satellite Imagery and Machine Learning <img src="https://github.com/cropmosaiks/NDVI_Images/blob/main/images/cropMOSAIKS_hex.png?raw=true" alt="logo" align="right" height=200px/>

## Purpose

This GitHub organization hosts the code and documentation used in a Capstone Project for the Masters of Environmental Data Science program at the Bren School of Environmental Science and Management, University of California Santa Barbara. This project intends to adapt, extend, and apply the MOSAIKS framework described in [Rolf et al. 2021](https://www.nature.com/articles/s41467-021-24638-z) to encode monthly imagery from the Landsat and Sentinel 2 satellite missions through random convolutional features over the years 2013 - 2021. The features are produced using an _unsupervised_ machine learning approach called random kitchen sinks. The resulting features are task-agnostic and therefore can be used to model a wide variety of tasks. The features are geolocated and can be geospatially joined to observed data to answer a plethora of questions. 

In this application of the MOSAIKS approach, the features are joined to crop yields in Zambia and a model is trained on this merged data using a _supervised_ machine learning approach, cross validated ridge regression. Our model is optimized for this specific task through systematically comparing model perfomance for various temporal subsetts including month and year range, spectral band combinations, spatially masking for cropland, several interpolation approaches, and weighted averages for features summarized to district levels. The optimized model is then applied to predict crop yields for this region for subsequent years in which Zambia lacks crop yield data: 2020 - 2021. This project is limited by data availability and is restricted to the country of Zambia.

## What is here?

This organization hosts three repositories including:
 1. [Featurization](https://github.com/mosaiks-capstone/Featurization)
 2. [Modeling](https://github.com/mosaiks-capstone/Modeling)
 3. [Visualizations](https://github.com/mosaiks-capstone/Visualizations)
 4. [Preprocessing](https://github.com/mosaiks-capstone/Preprocessing)

The top two repositories have independent README's that provide detailed explanations of their notebooks, data sources, and file organization. The third repository includes graphics generated for presentations.

## Contributing

The capstone project's completion date is June 9th, 2023. Some team members will be continuing work in this field and the repositories may stay active for some time to come. Suggestions for improvements to the code or documentation is welcome and encouraged. Please submit questions, comments, or code via issues or pull requests to the reposetories in this organisation. To correspond with the data scientists who produced these materials, please see their personal GitHub accounts listed below and feel free to contact them via email:

[Andrew Bartnik](https://github.com/andrewbartnik)\
[Carlo Broderick](https://github.com/CarloBroderick)\
[Hailey Veirs](https://github.com/gabriellensmith)\
[Gabrielle Smith](https://github.com/hveirs)

## Acknowledgements

Much of the code and copy in this organization was supported by or originates from the 2022 University of California, Santa Barbara, Bren School of Environmental Science and Management, Master of Environmental Data Science Capstone: [CropMOSAIKS An Open-source Pipeline for Remote Sensing of Crop Yields: a Zambia Case Study](https://github.com/cropmosaiks)

Much thanks to them and to Cullen Molitor for their support. 
