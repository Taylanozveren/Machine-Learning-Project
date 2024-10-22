# Machine-Learning-Project
IBM Data Science / The final project developed with explanations and comments
# Rain Prediction with Machine Learning

This project predicts whether it will rain tomorrow using historical weather data from Australia (2008-2017). The project applies various machine learning classification models to solve this binary classification problem.

## Dataset

The dataset used in this project is sourced from the [Australian Government Bureau of Meteorology](http://www.bom.gov.au/climate/dwo/). The dataset is named `weatherAUS.csv` and contains the following features:
- **Date**: Date of observation
- **Location**: Location of the observation
- **MinTemp**: Minimum temperature of the day (°C)
- **MaxTemp**: Maximum temperature of the day (°C)
- **Rainfall**: Amount of rainfall (mm)
- **WindSpeed**: Speed of the wind (km/h)
- **Humidity**: Percentage of humidity
- **RainTomorrow**: Target variable indicating if it rained the following day (Yes/No)

## Project Structure

The main components of the project are:

- `data/`: Contains the dataset file `weatherAUS.csv`.
- `notebook/`: Includes the Jupyter notebook used for training and evaluating the models (`Final Project: Classification with Python.ipynb`).
- `README.md`: This documentation file.
- `requirements.txt`: List of Python dependencies for setting up the project.
- `results/`: Contains the results of model evaluation (accuracy, F1-score, etc.).

## License

This project is licensed under the MIT License.
