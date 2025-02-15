# Comparative Analysis of Attention-Based and Convolution-Based Approaches for SITS Classification
[![rc](https://img.shields.io/badge/research%20compendium-ready-brightgreen)](#)

This repository contains code, data, and results for work replication. Based on a research compendium, all the data is available.

All the code in this work has been created using the R SITS package in version 1.5.2. To install it, use the command

```R
install.packages("sits")
```
To view notebooks:
  - [Notebook comparing attention and convolution-based approaches in Rondonia](https://geo-dl.netlify.app/rondonia_experiment)
  - [Notebook comparing attention and convolution-based approaches in Petrolina](https://geo-dl.netlify.app/petrolina_experiment)

## Repository organization:

-   [:file_folder: analysis](analysis) :arrow_right: Analysis code
   
-   [:file_folder: data/raw](data/raw) :arrow_right: Input data for notebooks
    -  [:file_folder: data/raw/samples/RO](data/raw/RO/samples) :arrow_right: Rondonia training samples
    -  [:file_folder: data/raw/samples/PE](data/raw/PE/samples) :arrow_right: Petrolina training samples
    -  [:file_folder: data/raw/validation/RO](data/raw/RO/validation) :arrow_right: Rondonia validation samples
    -  [:file_folder: data/raw/validation/PE](data/raw/PE/validation) :arrow_right: Petrolina validation samples

-   [:file_folder: data/output](data/output) :arrow_right: Outputs generated by the analysis
    -  [:file_folder: data/output/RO/classifications](data/output/RO/classifications) :arrow_right: Pixel-based classification results for Rondonia for each model
    -  [:file_folder: data/output/PE/classifications](data/output/PE/classifications) :arrow_right: Pixel-based classification results for Petrolina for each model
    -  [:file_folder: data/output/RO/model](data/output/RO/model) :arrow_right: Trained models for Rondonia
    -  [:file_folder: data/output/PE/model](data/output/PE/model) :arrow_right: Trained models for Petrolina
    -  [:file_folder: data/output/RO/tune](data/output/RO/tune) :arrow_right: Tuning results for Rondonia
    -  [:file_folder: data/output/PE/tune](data/output/PE/tune) :arrow_right: Tuning results for Petrolina
    -  [:file_folder: data/output/RO/segment](data/output/RO/segment) :arrow_right: Object-based classification results for Rondonia for each model
    -  [:file_folder: data/output/PE/segment](data/output/PE/segment) :arrow_right: Object-based classification results for Petrolina for each model

-   [:file_folder: docs](docs) :arrow_right: Site documentation
