# 🏠 housing-price-prediction

## Project Description
This project predicts housing prices based on features like square footage, number of bedrooms, bathrooms, and location. It is part of a data stewardship exercise making the experiment FAIR.

## Project Structure  

### Data  
- **House_Sales_King_County.csv** – Raw housing data (2014-2015)   

### Models  
- **gb_best_model.pkl** – Best Gradient Boosting model  
- **rf_best_model.pkl** – Best Random Forest model  
- **xgb_best_model.pkl** – Best XGBoost model  

### Notebooks  
- **Get_Data.ipynb** – Script to fetch data from DBRepo  
- **Modeling_Notebook.ipynb** – Full pipeline (EDA, modeling, evaluation)   

### Outputs  
- **evaluation_metrics.txt** – Test-set metrics (MAE, R², etc.)  
- **learning_rates_vs_r2.png** – XGBoost learning rate vs. performance plot  

### Configuration  
- **requirements.txt** – Python dependencies  
- **LICENSE** – CC BY 4.0 License   
- **codemeta.json** – Metadata (authors, dependencies, dataset PIDs) 

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
- Model, Code, and Scalers: CC BY 4.0

## Author
- Aleksandra Grishan


