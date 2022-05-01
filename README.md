# Efficient Hybrid Model For Hyperspectral Image Classification

<hr>

      Repo will be updated after publication :( 
      
<hr>

## Introduction 

### Hyperspectral remote sensing
- Hyperspectral remote sensing, also known as imaging spectroscopy, is a relatively new technology that is currently being investigated by researchers and scientists with regard to the detection and identification of minerals, terrestial vegetation, and man-made materials and backgrounds.
- Hyperspectral remote sensing combines imaging and spectroscopy in a single system which often includes large data sets and require new processing methods. Hyperspectral data sets are generally composed of about 100 to 200 spectral bands of relatively narrow bandwidths (5-10 nm), whereas, multispectral data sets are usually composed of about 5 to 10 bands of relatively large bandwidths (70-400 nm).
- Hyperspectral imagery is typically collected (and represented) as a data cube with spatial information collected in the X-Y plane, and spectral information represented in the Z-direction.

### Objective
use machine learning models to enchance this process
### Base
1) Remote sensing is the process of detecting and monitoring the physical characteristics of an area by measuring its reflected and emitted radiation at a distance

2) Unlike typical images(3 channel : RGB) , satellite images are compsed of multiple bands

        for example :
            consider a satellite with 5 bands and it can be as following : 
                - band 1 : red
                - band 2 : green
                - band 3 : blue
                - band 4 : shortwave infrared
                - band 5 : near infrared 
        more info : https://landsat.gsfc.nasa.gov/landsat-8/landsat-8-bands

3) so we will have multiple channels to work with

### Demo

            please check put root/DP_1.ipynb to get basic idea of HSI and it's classifiaction.
<hr>

in mean time you can check out metrices of proposed model : 

![image](https://user-images.githubusercontent.com/20265851/166126894-5c1c2e9b-8b87-4cab-9a69-53d75894abab.png)

![image](https://user-images.githubusercontent.com/20265851/166126910-ea687dfd-fe6d-4c59-ab84-230c429e33c7.png)

<hr>



