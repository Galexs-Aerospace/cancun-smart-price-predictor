# cancun-smart-price-predictor
A real-world machine learning system that predicts hotel / Airbnb / rental prices in Cancun using time-series, weather, holidays, and historical demand. 

## Goals 
- Build a multivariate time-series forescasting model.
- Explore baselines (LR, RF, XGBoost) and deep learning (LSTM, Temporal CNN, Transformer).
- Deploy a production-ready API.
- Demonstrate ML engineering best practices.

## Tech Stack 
- Python
- Pandas, Numpy
- Scikit-learn
- PyTorch
- FastAPI (later)
- Docker (later)

  ## Structure
  /data   # raw + processed datasets
  /notebooks  # exploration - modeling
  /src # reusable code
  /models   # saved weights
  /experiments   # metrics, plots, experiment configs
