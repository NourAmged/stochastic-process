# Hidden Markov Model for United States Weather Data Analysis

## Project Overview
This project involves analyzing weather data from the United States using a Hidden Markov Model (HMM). The goal is to uncover patterns and insights from historical weather data, which includes temperature, precipitation, wind speed, and sunshine duration. The project leverages Python and Jupyter Notebook for data analysis and modeling.

## Dataset
The dataset used in this project is `United_States_weather_data.csv`, which contains the following columns:

- **Country**: The country of the weather data (USA).
- **Date**: The date of the recorded data.
- **Temp_Max**: Maximum temperature recorded on the day (°C).
- **Temp_Min**: Minimum temperature recorded on the day (°C).
- **Temp_Mean**: Mean temperature of the day (°C).
- **Precipitation_Sum**: Total precipitation recorded (mm).
- **Windspeed_Max**: Maximum wind speed recorded (km/h).
- **Windgusts_Max**: Maximum wind gusts recorded (km/h).
- **Sunshine_Duration**: Total sunshine duration (seconds).

The dataset spans multiple days, providing a comprehensive view of weather patterns in the United States.

## Project Structure
- **HMM.ipynb**: A Jupyter Notebook containing the implementation of the Hidden Markov Model and the analysis of the weather data.
- **United_States_weather_data.csv**: The dataset used for analysis.

## Key Features
1. **Data Preprocessing**: Cleaning and preparing the weather dataset for analysis.
2. **Exploratory Data Analysis (EDA)**: Visualizing and understanding the trends and patterns in the weather data.
3. **Hidden Markov Model Implementation**: Using HMM to model and analyze the weather data.
4. **Results and Insights**: Extracting meaningful insights from the data and presenting them visually.

## Requirements
To run this project, you need the following:

- Python 3.x
- Jupyter Notebook
- Required Python libraries (install using the command below):

```bash
pip install numpy pandas matplotlib
```


## Implementation Details
This project implements a Hidden Markov Model (HMM) from scratch in Python. The implementation includes:

- **Custom HMM Class**: A Python class that defines the HMM with attributes for hidden states, observation symbols, state transition probabilities, emission probabilities, and initial state distribution.
- **Forward and Backward Algorithms**: Scaled implementations to prevent numerical underflow.
- **Baum-Welch Algorithm**: For training the HMM using observation sequences.
- **Viterbi Algorithm**: To find the most likely sequence of hidden states for a given observation sequence.
- **Likelihood Scoring**: To compute the log-likelihood of observation sequences.
- **Visualization**: Functions to visualize the state transition and emission probability matrices.

---

## Results
The results of the analysis include:
- Visualizations of weather trends over time (it capture seasonality overtime).
- Insights derived from the Hidden Markov Model, such as state transitions and probabilities.