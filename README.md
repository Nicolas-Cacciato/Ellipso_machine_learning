<h3 align="center"> Spectroscopic ellipsometric imaging: contribution of machine learning to data processing</h3>

## About The Project

This project, my master thesis, was about the addition of machine learning algorithm to data-processing.
In fact, the Spectroscopic ellipsometric imaging generates a large amount of data that takes considerable time to process.

The case treated is that of a multi-layer sample where we want to determine the thickness at each point.

For this, we used two type of data : Simulated data and experimental data (code will be added soon).

We start with Simulated data and make some analysis using similarity and a dimension reduction algorithm (T-sne).

Next, we used some clustering algorithm (Kmeans, Birch,...) to group the data allowing us to invert a less important number of spectra in order to obtain the thicknesses.

For the real data, we only used the Birch algorithm. The latter gave us better results in a shorter time.

References : 
- Steven J Byrnes. Multilayer optical calculations. arXiv preprint arXiv :1603.02720,2016.
- Michael Quinten. A Practical Guide to Optical Metrology for Thin Films : Quinten :optical metrology, 2012.
