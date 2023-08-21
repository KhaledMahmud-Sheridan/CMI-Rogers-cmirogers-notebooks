# CMI-Rogers Notebooks Repository
Welcome to the Jupyter Notebooks Repository! This repository contains a collection of Jupyter notebooks that cover various topics, ranging from data analysis to interactive visualizations.

## Table of Contents
- [Introduction](#introduction)
- [Notebook Descriptions](#notebook-descriptions)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contact](#contact)

## Introduction
Jupyter notebooks are a powerful tool for creating and sharing documents that contain live code, equations, visualizations, and narrative text. This repository aims to provide a curated set of Jupyter notebooks that demonstrate different concepts, techniques, and applications in a variety of fields.

## Notebook Descriptions
Here's a quick overview of the notebooks available in this repository:

- **GoogleMaps**: This folder contains notebooks to explore the Google Maps Routes API and determine other relevant Maps APIs that could be used to append information that may provide useful for analysis later (e.g. Maps Elevation API).

- **IEEE-BEV**: These notebooks were used to explore the parameters provided by [Steinstraeter (University of Munich)](https://ieee-dataport.org/open-access/battery-and-heating-data-real-driving-cycles) in their open dataset that has to do with a battery-powered electric vehicle.

- **Simscape**: These notebooks were used produced to explore the EV-related parameters which were output from the Simulink model produced by [Isaac Ito (Mathworks)](https://github.com/mathworks/Simscape-Battery-Electric-Vehicle-Model).

- **VED**: This notebook was used to explore the VED Dataset provided by [GS Oh (University of Michigan)](https://github.com/gsoh/VED) in order to view trends of the battery parameters as they are influenced by the environment and road traffic congestion.

## Getting Started
To get started with these Jupyter notebooks, follow these steps:
- Clone this repository to your local machine
    ```sh
    git clone https://github.com/your-username/jupyter-notebooks.git
    ```
- Unzip the **data** folder so that it is in the project root directory
- Create an `.env` file in your project root directory with the following info:
    ```python
    # Google Maps Routes API
    GOOGLE_MAPS_KEY = ""
    # HERE API
    HERE_API_KEY = ""
    # Geoapify API
    GEOAPIFY_KEY = ""
    
    ROOT_FOLDER = ""
    ```
    - Enter the required information as strings
    - ROOT_FOLDER refers to the project directory root
- Launch Jupyter Notebook by running the command `jupyter notebook` in your terminal.
- Navigate to the notebook of your choice and start exploring the content.

## Usage
Each notebook in this repository is designed to be self-contained and executable. You can modify the code, experiment with different parameters, and see the results in real-time. Feel free to use these notebooks for learning, practicing, and adapting the techniques to fit your needs.

## Notes
If you've found an issue or means of improvement in any of the notebooks, please don't hesitate to contact me.


## Contact
Jerikka Sotelo
soteloje@sheridancollege.ca