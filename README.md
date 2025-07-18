# 🏠 House Price Predictor

A machine learning-based **House Price Predictor** web application that estimates the price of a house in Bengaluru, India, based on various user-input features. Built using **Python**, **Scikit-learn**, and **Streamlit**, and trained on a cleaned dataset of real estate data.

---

## 🚀 Features

* Predicts house prices using a trained Ridge Regression model
* Interactive user interface built with Streamlit
* Based on real Bengaluru housing data
* Cleaned and preprocessed dataset included
* Model stored and reused using `RidgeModel.pkl`

---

## 📁 Project Structure

```
.
├── House_Price_Predictor.ipynb   # Jupyter notebook for EDA and model training
├── main.py                       # Streamlit app for deployment
├── RidgeModel.pkl                # Saved ML model (Ridge Regression)
├── Bengaluru_House_Data.csv      # Raw housing dataset
├── Cleaned_data.csv              # Cleaned and processed dataset
├── templates/                    # Web templates (if using Flask/HTML, optional)
├── .ipynb_checkpoints/           # Notebook checkpoints
├── README.md                     # Project documentation
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/house-price-predictor.git
cd house-price-predictor
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

If `requirements.txt` is missing, install manually:

```bash
pip install pandas numpy scikit-learn streamlit
```

### 3. Run the App

```bash
streamlit run main.py
```

---

## 📝 Usage

* Open the Streamlit interface in your browser
* Enter required inputs: location, BHK, bath, square footage, etc.
* Click **Predict Price**
* View the predicted house price instantly

---

## 📊 Model Info

* Algorithm: Ridge Regression
* Framework: Scikit-learn
* Evaluation metrics calculated in the notebook (`House_Price_Predictor.ipynb`)
* Model serialized using `joblib` or `pickle`

---

## 💼 Dataset

* **Bengaluru\_House\_Data.csv**: Raw dataset containing features like location, total\_sqft, bath, BHK, price, etc.
* **Cleaned\_data.csv**: Processed dataset used for training the ML model

Dataset Source: [Kaggle](https://www.kaggle.com/datasets)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙋️ Author

Developed by \[Your Name]. Contributions and suggestions are welcome!
