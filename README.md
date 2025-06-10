# Conformalized Quantile Regression in Time Series Forecasting

This repository contains the code corresponding to the Bachelor's thesis *"Conformalized Quantile Regression in Time Series Forecasting"*, by Martí Martínez Gargallo under the supervision of Dr. Jordi Vitrià Marca.

This repository presents the code corresponding to the data extraction and preprocessing, the training of the models, the application of CQR to the models, and their resulting evalutaion on real-world data.

It is possible that some notebooks, particularly those containing plots of different models, may not display correctly due to issues with GitHub. It is recommended to download and view them using Jupyter or Colab.

## Project Structure

The repository is organized into the following folders, each representing a key step in the forecasting pipeline:

- **01_extraction**  
  Contains the notebooks for data extraction from raw sources.

- **02_data_cleaning**  
  Includes teh notebooks for preprocessing and cleaning the extracted data.

- **03_training_test_selection_scaling**  
  Covers the selection of training and test sets, as well as the application of scaling techniques.

- **04_models**  
  Contains the implementation and training of forecasting models, including the application of CQR to these models. This folder is divided into one subfolder per model, where the training and evaluation of each model (with and without covariates) can be found, and a CQR folder containing all calibrated and then evaluated models.


- **05_examples**  
  Includes example visualizations of results produced by the trained models.

