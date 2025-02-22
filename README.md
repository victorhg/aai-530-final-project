# USD - DAAI 530 Final Project - Group 7 
Shiley-Marcos School of Engineering, University of San Diego AAI-500: Probability and Statistics

Group members
- Shaun Friedman
- Victoria Dorn
- Victor Hugo Germano

Files
- [Driver Folder with documents and colaboration files](https://drive.google.com/drive/u/1/folders/1Ho0cbkQrALTQ1QajB23yyNN9-QqUVm4Z)

## Introduction

This project aims to leverage time series sensor data to better understand the interplay between environmental and infrastructural factors influencing traffic and air quality in Aarhus, Denmark. By combining datasets from road traffic, weather, parking, and city events, we aim to build predictive models that assist urban planners, city administrators, and the public in making data-driven decisions on transportation and environmental management. 

This repository utilizes a Docker-based environment, called a Development Container, designed to provide a consistent and reproducible setup work. Using development containers ensures that all dependencies and configurations are standardized, making it easier to collaborate across different environments and systems. We also utilize Jupyter Notebooks for their flexibility and ease of use. They allow us to run code in chunks, display rich outputs like graphs and visualizations, and combine code with markdown documentation for clear explanations. 

## Prerequisites
1. Docker: Install Docker on your machine. Follow the instructions here to get Docker installed.
2. Visual Studio Code: Install Visual Studio Code from here.
3. Remote - Containers Extension: Install the "Remote - Containers" extension for VS Code from the Extensions Marketplace.

## Quick Start Guide

1. Begin by cloning the repository that contains the development container configuration:

```
git clone <repository-url>
cd <repository-directory>
```

2. Open the Project in VS Code. `code .`
3. Rebuild and Open the Container. Use the Command Palette (Ctrl+Shift+P or Cmd+Shift+P on macOS) to select Remote-Containers: Rebuild Container. VS Code will build the Docker image based on the configuration in the .devcontainer directory and open the project inside the container.
4. Once inside the development container, you can use juputer notebooks (without an exposed port). **NOTE: the data needs to be downloaded into the `data` folder to go through preprocessing, but the data used to train our models is already there.**

## Repository Structure



## Additional Features

#### Eporting a Jupyter Notebook as PDF. 

You can add a `--output` flag if you want to specify the output file name otherwise it will use the file_name of your .ipynb.
```
jupyter nbconvert --to pdf <file_name.ipynb>
```

## TODO
[] Data Ingestion & Preprocessing
    - Weather Dataset - Tori
    - Road Traffic & Parking - Shaun
    - City Events (Library & Culture) - Victor
[] Dataset Combinations
[] Model Selection
[] Model Training

## Reference

- [USD Final Project Reference Document](https://sandiego.instructure.com/courses/17674/pages/review-final-team-project-description?module_item_id=663812)
