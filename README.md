# Quaternion-generic-Fourier-descriptor-QGFD-
This repository provides code of Quaternion generic Fourier descriptor (QGFD) for color object recognition.

<img alt="scratch" src="QGFD.png" width='500'>  
<sub><b>Figure 1: </b> The main idea of QGFD. </sub> 

GFD_main.m is to show calculation of generic Fourier descriptor for an image.
QGFD_main.m is to show calculation of calculate quaternion generic Fourier descriptor for an image.
qgfd.m, input a color image and output the feature of QGFD.
center.m and imc2q.m are subfunctions for the calution of QFGD.

Quaternion toolbox for Matlab is necessary to use this package. It is available from Sangwine's personal page, http://privatewww.essex.ac.uk/~sjs/.

Details of QGFD refer to Li H, Liu Z, Huang Y, et al. Quaternion generic Fourier descriptor for color object recognition[J]. Pattern Recognition, 2015, 48(12): 3895-3903.
