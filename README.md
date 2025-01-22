# Netflix Stock Market Prediction

## Overview
This project involves predicting Netflix's stock prices using traditional Machine Learning (ML) algorithms. By analyzing historical stock market data, we aim to forecast future stock prices with the help of regression techniques and other classical ML methods.

## Features
- **Data Collection**: The dataset used in this project consists of historical Netflix stock prices obtained from [Yahoo Finance](https://finance.yahoo.com) or similar reliable sources.
- **Data Preprocessing**: Handled missing values, normalized the data, and split it into training and testing sets.
- **Exploratory Data Analysis (EDA)**: Visualized the data trends and performed statistical analysis.
- **Modeling**: Used traditional ML algorithms like Linear Regression, Decision Trees, and Random Forest to predict stock prices.
- **Evaluation**: Assessed the models' performance using metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared value.

## Dependencies
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/sahankrt20/netflix-stock-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd netflix-stock-prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Ensure you have the dataset (`NFLX.csv`) in the `data/` directory.
2. Run the `main.py` script to train the model and make predictions:
   ```bash
   python main.py
   ```
3. The script will output evaluation metrics and save visualizations of predicted vs actual stock prices in the `results/` directory.

## Results
- **Performance**: The Decision tree model achieved the best results with an R-squared value of 0.95 on the test set.
- **Insights**: Observed strong correlations between stock prices and specific time features like moving averages.

## Future Work
- Integrate advanced techniques like LSTMs for time series prediction.
- Incorporate external factors such as market sentiment analysis and news data.
- Develop a web-based dashboard for real-time stock predictions.

## Contributing
Feel free to fork this repository, submit issues, and create pull requests to improve the project.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

