# 📈 Google & Tesla Stock Price Prediction

This repository includes two projects focused on stock price prediction:

- 📉 **Tesla Stock Price Prediction using Linear Regression**
- 🤖 **Google Stock Price Prediction using LSTM (Deep Learning)**

Each model uses historical stock price data and predicts future prices using different machine learning approaches.

---

## 📂 Project Structure

```
├── Google_stock_price.ipynb              # Google stock price prediction using LSTM
├── Tesla_stock_price_prediction.ipynb    # Tesla stock price prediction using Linear Regression
├── data/
│   ├── tesla.csv                         # Tesla stock data
│   ├── Google_train_data.csv             # Google training data
│   └── Google_test_data.csv              # Google testing data
├── requirements.txt                      # Python dependencies
├── .gitignore                            # Git ignore rules
└── README.md                             # Project documentation
```

---

## 🧪 Technologies & Libraries Used

- **Python**
- **Jupyter Notebook**
- **Pandas, NumPy** – Data processing
- **Matplotlib, Plotly** – Data visualization
- **Scikit-learn** – Linear regression, scaling, metrics
- **Keras (TensorFlow backend)** – LSTM implementation
- **yfinance** (optional) – For live stock data (if extended)

---

## 📊 Model Overview

### 1️⃣ Tesla Stock Price – Linear Regression

- Uses scikit-learn's Linear Regression.
- Visualizes actual vs predicted prices using Plotly.
- Includes R² score and Mean Squared Error (MSE) for evaluation.

### 2️⃣ Google Stock Price – LSTM Neural Network

- Uses Keras Sequential API.
- Deep learning with 4 stacked LSTM layers and Dropout.
- Trained on 60 time steps and tested using separate test data.
- Uses MinMaxScaler for normalization.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Stock-Price-Prediction.git
cd Stock-Price-Prediction
```

### 2. Set Up Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate     # On Windows use: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run Jupyter Notebook

```bash
jupyter notebook
```

Open the desired notebook:

- `Tesla_stock_price_prediction.ipynb`
- `Google_stock_price.ipynb`

---

## 📁 Dataset Info

Place the following datasets inside the `/data/` directory:

- `tesla.csv`
- `Google_train_data.csv`
- `Google_test_data.csv`

If you're missing these files, they can be sourced from Yahoo Finance or any stock API, or generated using the `yfinance` library.

---

## 📈 Results

- **Tesla**: Visual comparison between actual and predicted prices with regression line.
- **Google**: LSTM-based predictions vs actual prices shown via matplotlib.

---

## ⚙️ Requirements

See `requirements.txt` for full details. Key packages include:

```
pandas
numpy
matplotlib
plotly
scikit-learn
tensorflow
keras
nbformat
```

---

## 📜 License

This project is licensed under the MIT License.

---

## 🤝 Contributions

Contributions, issues, and pull requests are welcome!

---

## 📬 Contact

For any queries or collaborations, feel free to reach out via GitHub or email.
