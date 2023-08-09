# Disp-velib

Disp-velib is a data analysis and visualization project focused on historical data from vélib bike-sharing stations.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)

## Introduction

Disp-velib is a project aimed at exploring the historical usage patterns of vélib bike-sharing stations. 
It provides insights into relevant metrics, and, hopefuly, station capacity prediction.

## Installation

To set up the project, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/LegrandA/disp_velib
    ```

2. Navigate to the project directory:

    ```bash
    cd disp_velib
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the analysis and generate visualizations, execute the following commands:

```bash
#TODO
```

Generated visualizations will be saved in the `output/` directory.

## Data

The historical vélib bike-sharing station data used in this project can be downloaded from the following link:

[Download Data](https://github.com/lovasoa/historique-velib-opendata/releases/download/new/stations.zip)

After downloading the data, unzip the contents and place the extracted files in the `data/` folder of this project before running the analysis script.

The `data/` folder should have the following structure:

```
disp-velib/
│   README.md
│	analyze.ipynb
│   ...
└───data/
    │   historique_stations.csv
    │   ...