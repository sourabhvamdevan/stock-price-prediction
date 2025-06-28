# stock-price-prediction

This project builds a stock price prediction pipeline for NSE-listed stocks (e.g., Reliance Industries) using machine learning ensemble models. The final model ensemble (Gradient Boosting, AdaBoost, Random Forest) achieves moderate accuracy (R² ≈ 0.68) on unseen stock data.

# features

Fetches real-time historical stock data using yfinance

Generates moving average features (MA10, MA20)

Implements and compares:

Gradient Boosting Regressor (GBR)

AdaBoost Regressor

Random Forest Regressor

Stacking Regressor (ensemble of the above)

Evaluates using R² score

Visualizes actual vs predicted prices using Matplotlib

 # Tech Stack

| Category        | Tools/Libraries Used                             |
| --------------- | ------------------------------------------------ |
| **Language**    | Python 3                                         |
| **Data Source** | [`yfinance`](https://pypi.org/project/yfinance/) |
| **Libraries**   | `pandas`, `numpy`, `matplotlib`, `scikit-learn`  |
| **Models**      | GBR, AdaBoost, Random Forest, Stacking           |
| **IDE**         | Jupyter Notebook (`.ipynb`)                      |



