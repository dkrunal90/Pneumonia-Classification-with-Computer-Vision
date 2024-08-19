# Pneumonia-Classification-with-Computer-Vision

For my final project I wanted to expand my computer vision repetoir. Last term in supervised learning I did rice image classification from a very clean dataset with very standardized file names. I want to practice using the os.listdir() to programatically clean messy file names.

The data I will use can be found at Mendeley Data. The data contain images of both chest X-Rays and Optical Coherence Tomography. I will use the chest X-rays in this project, but I think in another project I'll use the OCT data.

Here's my general plan of attack:

Import and clean the data. I'll use PCA to reduce the image sizes for modelling purposes.

Perform an EDA. I'll do this on the untransformed data for human comprehensibility. I will allow the user to pick a feature to analyze!

Build unsupervised models. I'll use sklearn's library for two models: NMF, and KMeans.

Compare against a supervised model. Because I wich to do this, I will be careful during data importation so that I can easily transition to a Random Forest.
