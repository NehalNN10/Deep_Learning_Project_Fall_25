# Predicting Desertification in Thar Desert Using Deep Learning

This project aims to use different machine learning and deep learning architectures and techniques to tackle an emerging climate problem - Desertification.

Desertification is the process where the area outside a desert region becomes a part of it due to climate change and global warming.

Our area of interest for this study is the Thar Desert, located in the Western part of the Indian subcontinent.

<!-- ![Map of Area of Interest](map\files/aoi.png) -->
![Map of Area of Interest](<map files/aoi.png>)

This repository contains the map files (.kml) used to define the area of the desert, the notebooks used for extracting and making the data files from the Google Earth Engine using their Python API (you will need to create a Google Cloud Project for this), and the models that were trained on the different data sources to predict future trend of the desert.

The main sources of data are the Dynamic World LULC (land use land cover) from Sentinel 2, serving as our ground truth, and the raw spectral values obtained from Modis satellite that are used by some models with computed vegetation indices. The spatio-temporal alignment between the two source is handled alongside their extraction code.  

The four models used in the study are:
1. Neural Cellular Automata
2. PredRNN
3. Transformer Cellular Automata Hybrid
4. Cellular Automata Markov Model

The work was accepted to the IEEE IGARSS 2026 conference.

Refer to the [poster](Project\Report.pdf) and [report](Poster.svg) in the repository for more details.


