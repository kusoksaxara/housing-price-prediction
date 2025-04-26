# housing-price-prediction

## Project Description
This project predicts housing prices based on features like square footage, number of bedrooms, bathrooms, and location. It is part of a data stewardship exercise making the experiment FAIR.

## Input Data
- Source: OpenML House Sales Dataset: https://www.openml.org/search?type=data&status=active&id=42092&sort=runs
- Number of samples: 4600
- Features: date, price, bedrooms, bathrooms, sqft_living, etc.

## Experiment
- Training set: 70% of data
- Validation set: 15% of data
- Test set: 15% of data

Data subsets are stored in DBRepo with persistent identifiers (PIDs).

## Code
The notebook loads data subsets from DBRepo using their API, trains a model, and evaluates its performance.

## Metadata Standards
- FAIR

## How to Run
1. Set up a Python environment
2. Install required libraries
3. Run the notebook

## License
This project is licensed under the MIT License.

## Author
- Aleksandra Grishan


