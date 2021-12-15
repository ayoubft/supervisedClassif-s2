# Supervised classification based on pixels

For this work we used a Sentinel-2 satellite image from the USGS site, of the Nador region in the north of Morocco, the spectral bands of the R, G, B and NIR channels are used.

The basic idea is to take the radiometric values of the different bands of the satellite image, flatten them and then train the famous `KNN` algorithm of [sklearn](https://scikit-learn.org/).

Jump to: [the jupyther notebook](https://github.com/ayoubft/supervisedClassif-s2/blob/main/landUseClassif-en.ipynb).
