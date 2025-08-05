
# 🌍 Climate Change Prediction using LSTM (Google Colab Project)

This project demonstrates how deep learning (LSTM) can be used to predict climate trends based on historical data. The model is trained on a multivariate time series climate dataset, and the entire workflow is done in **Google Colab** for ease of accessibility and sharing.

---

## 📌 Project Highlights

- ✅ Built using Google Colab  
- ✅ Uses LSTM (Long Short-Term Memory) neural networks  
- ✅ Takes multivariate climate data as input  
- ✅ Scales and sequences time-series data  
- ✅ Visualizes actual vs. predicted values  
- ✅ Optional Flask web app integration for real-time predictions

---

## 🧠 Technologies Used

- Python  
- TensorFlow / Keras  
- Pandas, NumPy, Matplotlib  
- Scikit-learn  
- Google Colab (Notebook)  
- Flask (optional for web API)

---

## 🗂️ File Structure

```
📁 climate-predictor/
├── climate_lstm_colab.ipynb      # Main Colab notebook
├── climate_large_dataset.csv     # Dataset used for training
├── app.py                        # Optional Flask API (if used)
├── templates/
│   └── index.html                # Frontend for Flask app
├── requirements.txt              # Python dependencies (optional)
└── README.md                     # Project documentation (this file)
```

---

## ▶️ How to Use

### 📍 In Google Colab

1. Open the notebook `climate_lstm_colab.ipynb` in Google Colab.
2. Upload your dataset (`climate_large_dataset.csv`) when prompted.
3. Run all the cells step-by-step.
4. View prediction plots and results at the end of the notebook.

### 🌐 Optional: Run Flask App Locally

If you want to serve predictions via a web interface:

```bash
# Step 1: Clone the repo
git clone https://github.com/yourusername/climate-predictor.git
cd climate-predictor

# Step 2: Install dependencies
pip install -r requirements.txt

# Step 3: Run Flask app
python app.py
```

Then visit `http://127.0.0.1:5000` in your browser.

---

## 📊 Sample Input Format (Frontend)

To make predictions via the web app, enter data like this in the textbox:

```
0.2,0.4,0.1; 0.3,0.5,0.2; 0.4,0.6,0.3; ...
```

- Each group (e.g. `0.2,0.4,0.1`) is one timestep with all variable values  
- Separate timesteps with `;`

---

## 🧾 Requirements

You can generate a `requirements.txt` with this:

```txt
flask
numpy
pandas
tensorflow
scikit-learn
```

---

## 💡 Future Improvements

- Deploy the app using Streamlit or on Hugging Face Spaces  
- Use larger datasets and deeper models  
- Add forecasting for multiple future days  
- Integrate weather APIs for live data

---

## 🏷️ Tags

`#AI4Climate` `#LSTM` `#GoogleColab` `#DeepLearning` `#Flask` `#ClimateAction`

---

## 📄 License

MIT License – feel free to use and adapt this project!
