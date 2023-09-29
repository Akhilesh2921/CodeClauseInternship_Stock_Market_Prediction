# CodeClause Internship Stock Market Prediction

This repository contains a Python script that uses Long Short-Term Memory (LSTM) neural networks to predict stock prices for Nifty 50 companies. Users can select a company symbol and a prediction date, and the script trains an LSTM model to make predictions.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

- Python 3.x
- Libraries mentioned in `requirements.txt`. You can install them using pip:

```shell
pip install -r requirements.txt
```

## Getting Started

1. Clone this repository to your local machine:

```shell
git clone https://github.com/Akhilesh2921/CodeClauseInternship_StockMarketPrediction.git
```

2. Navigate to the project directory:

```shell
cd CodeClauseInternship_StockMarketPrediction
```

3. Run the script:

```shell
python stock_price_prediction.py
```

## Usage

1. When you run the script, you will be prompted to select a company symbol and a prediction date.

2. The script will train an LSTM model on historical stock price data and make predictions for the selected company.

3. Evaluation metrics, including RMSE, MAE, and R-squared, will be displayed in the console.

4. Plots showing the training and validation loss and the actual vs. predicted stock prices will also be generated.

## Results

You can find the results of the stock price prediction in the generated plots and in the console output. These results will help you assess the model's performance.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:

```shell
git checkout -b feature/my-feature
```

3. Make your changes and commit them:

```shell
git commit -m "Add my feature"
```

4. Push your changes to your fork:

```shell
git push origin feature/my-feature
```

5. Create a pull request on the main repository's branch.

Please ensure that your code adheres to the project's coding standards and includes appropriate documentation.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```
