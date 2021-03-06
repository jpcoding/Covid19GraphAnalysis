# Covid19GraphAnalysis

This repository includes datasets used in the paper __*Graph-Based Analysis of COVID-19 Transmission Using State- and County-Based Location Exposure Index*__. 

The datasets cover the follwing dates: 2020-03-1, 2020-03-08, 2020-03-15, 2020-03-22, 2020-03-22, 2020-04-05. 

__LEX.ipynb__ : preprocess the LEX data.

__cases.ipynb__: preprocess the case data.

__Case-date.csv__ : the accumulative case on the six days. 

__LEX-date.csv__: linked county pairs that have travellers between them. The defination of LEX can be found in this repository: https://github.com/COVIDExposureIndices/COVIDExposureIndices

__query code.txt__: Cypher code (neo4j) to build and query the graph database using the dataset in this repository. 
