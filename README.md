# EDA_Collec

A collection of Exploratory Data Analysis (EDA) notebooks across multiple real-world datasets and domains.

## Project Overview

This repository contains independent EDA mini-projects focused on:

- data cleaning and preprocessing
- descriptive statistics
- visualization with Matplotlib/Seaborn (and Plotly in some notebooks)
- feature understanding for downstream modeling

## Repository Structure

- `Bill Tips Analysis/Tips_EDA.ipynb`
- `Covid-19 in India Analysis/Covid-19 Analysis.ipynb`
- `Flight Analysis/flight.ipynb`
- `Netflix Data Analysis/Netflix_Analysis.ipynb`
- `Playstore_Apps Analysis/Playstore.ipynb`
- `RedWineAnalysis/Red Wine EDA.ipynb`
- `Spotify Data Analysis/Spotify_Analysis.ipynb`
- `Student performance Analysis/Student_Performance_EDA.ipynb`
- `TitanicSurv Analysis/Titanic_EDA.ipynb`
- `Water Quality Analysis/Quality_Analysis.ipynb`

## Datasets Used

- `Bill Tips Analysis`: uses Seaborn built-in dataset (`tips`)
- `Covid-19 in India Analysis`: `covid_19_india.csv`, `covid_vaccine_statewise.csv`
- `Flight Analysis`: `flight_price.xlsx`
- `Netflix Data Analysis`: `netflix_titles.csv`
- `Playstore_Apps Analysis`: `playstore.csv`
- `RedWineAnalysis`: `red.csv`
- `Spotify Data Analysis`: `tracks.csv`, `SpotifyFeatures.csv` (also contains `artists.csv`)
- `Student performance Analysis`: `stud.csv`
- `TitanicSurv Analysis`: uses Seaborn built-in dataset (`titanic`)
- `Water Quality Analysis`: `water_potability.csv`

## Tech Stack

Main Python libraries used across notebooks:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `plotly` (selected notebooks)
- `scikit-learn` (flight notebook feature engineering)

## Setup

1. Clone this repository.
2. Create and activate a virtual environment.
3. Install required packages:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn jupyter openpyxl
```

`openpyxl` is needed for reading Excel files (`flight_price.xlsx`).

## Running the Notebooks

From the repository root:

```bash
jupyter notebook
```

Then open any notebook in its folder and run cells in order.

## Notes

- Keep each notebook in its current folder so relative dataset paths continue to work.
- For notebooks using Seaborn built-in datasets (`tips`, `titanic`), internet access may be required the first time they  are   fetched