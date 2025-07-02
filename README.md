# Flight Ticket Price Prediction Model

## Overview
This project is part of the Machine Learning Practice (MLP) curriculum in the IITM BS Degree program. The goal of this project is to predict the price of flight tickets based on various features provided in the dataset. This was developed as part of Kaggle Assignment-1 for Term-2 in 2025.

## Dataset Description
The dataset consists of flight information with several features that influence the price of flight tickets. The task is to predict the ticket price based on these features.

### Files
- `train.csv`: The training set containing features and the target variable.
- `test.csv`: The test set for which the target column (price) is hidden.
- `sample_submission.csv`: A sample submission file in the correct format.

### Column Descriptions
| Column | Description |
|--------|-------------|
| airline | Name of the Airline company |
| flight | Information about flight code |
| source | City from which the flight takes off |
| departure | Time period at which the flight takes off |
| stops | Number of stops between source and destination cities |
| arrival | Time period at which the flight lands |
| destination | City where the flight lands |
| class | Information about seat class |
| duration | Overall time taken to travel between cities in hours |
| days_left | Number of days between booking and trip dates |
| price | Information about ticket price |

## Project Structure
- `data/`: Directory containing the dataset files.
- `notebooks/`: Jupyter notebooks used for data exploration, preprocessing, model training, and evaluation.
- `scripts/`: Python scripts for various stages of the data processing and modeling pipeline.
- `models/`: Saved models and model-related files.
- `README.md`: Project overview and instructions.

## Installation
To run this project locally, you need to have Python installed along with the necessary libraries. You can install the required libraries using pip:

```bash
pip install -r requirements.txt
