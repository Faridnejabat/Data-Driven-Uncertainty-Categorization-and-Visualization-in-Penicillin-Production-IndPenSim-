# Master-s-Thesis---Uncertainty-Categorization-and-Visualization-in-Penicillin-Production-IndPenSim-
## Overview
This project is built upon the simulation of penicillin production as outlined in the paper ["Modern day monitoring and control challenges outlined on an industrial-scale benchmark fermentation process"](https://www.sciencedirect.com/science/article/pii/S0098135418305106). The simulation was conducted in MATLAB 2018b, and the data generated from the simulation can be found on [Mendeley Data](https://data.mendeley.com/datasets/pdnjz7zz5x/1).
## Data Description
The data represents a 100,000 litre penicillin fermentation system (referred to as IndPenSim) and is designed for advanced data analytics, machine learning (ML), or artificial intelligence (AI) algorithms applicable to the biopharmaceutical industry.

### Key Features:
100 batches of data generated using various control strategies:
- Batches 1-30: Controlled by a recipe-driven approach.
- Batches 31-60: Controlled by human operators.
- Batches 61-90: Controlled by an Advanced Process Control (APC) system using Raman spectroscopy.
- Batches 91-100: Include faults and process deviations.
Data Size: ~2.5 GB
Source: IndPenSim provides a realistic simulation including Raman spectroscopy data for developing and evaluating control solutions in biotechnology.

## Objective
The goal of this project is to categorize and visualize uncertainties within each batch, based on the control strategies applied. By defining key Critical Process Parameters (CPP) (e.g., PAA concentration) and Critical Quality Attributes (CQA) (e.g., Penicillin & Biomass concentration), the project ranks each batch and plots them based on their performance and precision.

## Features
This repository contains all the code and analysis required to:

- Rank each batch based on its performance against defined CPPs and CQAs.
- Visualize the uncertainties and precision of batch performance under different control strategies.
- Provide insights into the performance deviations caused by control faults.

The pipeline includes:

Data Preprocessing: Handling raw data from the simulation.
Uncertainty Categorization: Defining criteria and ranking batches using statistical analysis.
Visualization: Plotting the ranked performance for further analysis. (Final Visualization has done using Tableau)

## Data
You can download the full dataset from [Mendeley Data](https://data.mendeley.com/datasets/pdnjz7zz5x/1). The dataset is not included in this repository due to its large size (~2.5 GB).

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact
For questions or further information, feel free to contact:

Name: Farid Nejabat
Email: farid.nejabat97@gmail.com
Phone: +43 678 7800 846
