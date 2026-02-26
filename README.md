# Store Sales Prediction

A machine learning project for predicting store sales using time series forecasting techniques.

## Overview

This project analyzes and predicts store sales using historical data, oil prices, store information, and holiday data. The model leverages advanced time series forecasting libraries to provide accurate sales predictions.

## Features

- Time series analysis and forecasting
- Data preprocessing and feature engineering
- Missing value analysis and handling
- Integration with MongoDB for data storage
- Visualization of sales trends and patterns
- Multiple forecasting models using Darts library

## Dataset

The project uses four main datasets:
- **Sales Data**: Historical sales records
- **Oil Prices**: Daily oil price data
- **Store Information**: Store metadata and characteristics
- **Holidays**: Holiday calendar data

## Technologies Used

- **Python 3.10+**
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib & Seaborn**: Data visualization
- **Darts**: Time series forecasting
- **PyMongo**: MongoDB integration
- **Scikit-learn**: Machine learning utilities
- **XGBoost**: Gradient boosting models

## Installation

1. Clone the repository:
```bash
git clone https://github.com/[username]/store-sales-prediction.git
cd store-sales-prediction
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Set up MongoDB credentials (if using database):
   - Create a `.env` file or configure your MongoDB connection string
   - Update the connection details in the notebook

## Usage

1. Open the Jupyter notebook:
```bash
jupyter notebook Store_sales_prediction.ipynb
```

2. Run the cells sequentially to:
   - Load and preprocess data
   - Perform exploratory data analysis
   - Train forecasting models
   - Generate predictions

## Project Structure

```
store-sales-prediction/
│
├── Store_sales_prediction.ipynb    # Main analysis notebook
├── requirements.txt                 # Python dependencies
├── README.md                        # Project documentation
├── .gitignore                       # Git ignore rules
└── LICENSE                          # License file
```

## Results

The model provides sales forecasts with visualizations showing:
- Historical sales trends
- Predicted future sales
- Model performance metrics
- Feature importance analysis

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For questions or feedback, please open an issue in the repository.
