# 🚗 Car Price Prediction 🏷️

Welcome to the Car Price Prediction project! 🚀 This project builds a machine learning model to estimate the price of used cars based on their features. From data cleaning to model training and a snazzy GUI, this project has it all. Dive in and explore!

## 📚 Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [GUI Implementation](#gui-implementation)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## 🚀 Project Overview

This project aims to predict the resale price of cars using a dataset with various features. We clean and preprocess the data, train a linear regression model, and create an interactive GUI for easy predictions. Perfect for anyone interested in data science and machine learning!

## 📊 Dataset

The dataset includes:
- **`name`**: Name of the car
- **`company`**: Manufacturer
- **`year`**: Year of manufacture
- **`kms_driven`**: Total kilometers driven
- **`fuel_type`**: Type of fuel (Petrol, Diesel, LPG)
- **`Price`**: Target variable - car price

## 🧹 Data Cleaning

We cleaned the dataset by:
- Fixing non-numeric values in the `year` column and converting to integers.
- Handling missing and erroneous values in `Price` and `kms_driven`.
- Standardizing the `name` column to keep only the first three words.
- Removing price outliers to ensure accurate predictions.

## 🔍 Exploratory Data Analysis

Explore relationships between features and car prices with various plots:
- Box plots 🧳 for company vs. price
- Scatter plots 🔭 for year vs. price
- Relational plots 📈 for kilometers driven vs. price
- Fuel type analysis 🚘

## 📈 Modeling

We used a linear regression model with:
- **One-hot encoding** for categorical features (`name`, `company`, `fuel_type`)
- **Linear regression** to predict car prices

## 📉 Evaluation

The model's performance was assessed using the R-squared (R²) metric. After testing multiple random states, the best model achieved an R² score of approximately 0.65. 🎯

## 🖥️ GUI Implementation

Interactive GUI built with `ipywidgets` allows users to input car details and get price predictions. 🌟
- **Input fields**: Car name, company, year, kilometers driven, fuel type
- **Predict button**: Get instant price predictions!

## 💻 Installation

To set up the project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/car-price-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd car-price-prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook to interact with the model and GUI:
   ```bash
   jupyter notebook
   ```

## 🏗️ Usage

1. Open the Jupyter Notebook and run the cells.
2. Use the GUI to input car details and see the predicted price.

## 🤝 Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue to discuss changes. Let’s make this project even better together!



---

Feel free to customize this further if there’s anything specific you want to highlight or adjust!
