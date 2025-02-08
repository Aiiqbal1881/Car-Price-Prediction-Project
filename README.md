# Car-Price-Prediction-Project

# Car Price Prediction

## Overview
This project aims to predict the price of a car based on various features such as mileage, engine size, horsepower, and other relevant attributes. The model is built using **Machine Learning (ML)** techniques, specifically **Linear Regression** and **Lasso Regression**, implemented in **Python**. Data visualization is performed using **Matplotlib** and **Seaborn** to analyze relationships between features and the target variable.

## Technologies Used
- **Python**: Programming language used for data processing, modeling, and visualization.
- **Machine Learning (ML)**: Applied supervised learning algorithms to predict car prices.
- **Linear Regression**: A statistical method used to model the relationship between independent variables and car prices.
- **Lasso Regression**: A type of regression that adds L1 regularization to improve model performance and feature selection.
- **Matplotlib**: Used for data visualization and graphical representation.
- **Seaborn**: Used for enhanced statistical data visualization.

## Dataset
The dataset consists of various attributes that influence car pricing, including:
- **Brand & Model**
- **Year of Manufacture**
- **Engine Size**
- **Mileage**
- **Horsepower**
- **Fuel Type**
- **Transmission Type**
- **Price** (Target Variable)

## Project Structure
```
Car-Price-Prediction/
│-- data/                      # Contains dataset files
│-- notebooks/                  # Jupyter notebooks for analysis & modeling
│-- src/                        # Source code for preprocessing and modeling
│   │-- preprocess.py           # Data cleaning and preprocessing
│   │-- train_model.py          # Model training and evaluation
│-- requirements.txt            # Required Python packages
│-- README.md                   # Project documentation
```

## Installation
To run this project, install the required dependencies by executing:
```bash
pip install -r requirements.txt
```

## Usage
1. **Data Preprocessing**: Run `preprocess.py` to clean and prepare the dataset.
2. **Training the Model**: Use `train_model.py` to train the regression models.
3. **Visualization**: Use Jupyter notebooks to analyze data trends using Seaborn and Matplotlib.

## Results
- The model outputs predicted car prices based on the given features.
- Lasso Regression helps in feature selection by reducing less important features to zero.
- Visualizations provide insights into correlations between car features and pricing.

## Contributing
Feel free to contribute to this project by submitting pull requests or reporting issues.

## License
This project is licensed under the MIT License.

## Acknowledgments
- **Scikit-Learn** for providing ML algorithms.
- **Pandas & NumPy** for data handling.
- **Matplotlib & Seaborn** for visualization

