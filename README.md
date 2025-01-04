# Used-Car-Price-Prediction
The Machine Learning model predicts used car price prediction. The models used are CART, Linear Regression and RandomForest Algorithms.

# Project Name

## Overview
This repository contains a Jupyter Notebook (`Project.ipynb`) that implements used car price prediction. The notebook demonstrates key functionalities such as data preprocessing, visualization, and statistical analysis. It is designed for data scientists, analysts, or developers interested in understanding customer behavior through sales data.

## Features
- **Data Preprocessing**:
  1. Cleans all the null values using Numpy and Pandas.
  2. Assign numbers to enum values.
  3. Remove the units as the model cannot process units.
  4. Encode all the categorical data.
- **Visualization**:
  1. Visualized all the necessary features using seaborn and matplotlib.
  2. Created correlation matrix to understand the important factors that affect price.
     
- **Analysis**:
  1. Used Linear Regression, CART Model and Random Forest Regressor to predict car prices.

## Prerequisites
To run the notebook, ensure the following are installed:

- Python 3.x
- Jupyter Notebook or Jupyter Lab
- Required Python libraries:
  ```bash
  pip install -r requirements.txt
  ```

## Usage
1. Clone the repository:
   ```bash
   git clone (https://github.com/ubl2/Used-Car-Price-Prediction.git)
   ```
2. Navigate to the project directory:
   ```bash
   cd Used-Car-Price-Prediction
   ```
3. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook Project.ipynb
   ```
4. Execute cells sequentially to reproduce the results or explore the workflow.

## File Structure
- `Project.ipynb`: The main Jupyter Notebook containing the implementation.
- `requirements.txt`: List of dependencies.
- `data/`: Directory for input datasets (if applicable).


## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any suggestions or improvements.



