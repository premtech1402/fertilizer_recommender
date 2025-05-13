# 🌾 Fertilizer Recommendation System

This project predicts the most suitable **fertilizer** based on soil conditions, crop type, and nutrient levels using a trained machine learning model. It helps farmers make informed decisions to improve crop yield and maintain soil health.

---

## 🚀 Features

- Predicts the best fertilizer based on:
  - Temperature
  - Humidity
  - Moisture
  - Soil Type
  - Crop Type
  - Nitrogen, Phosphorous, Potassium levels
- Clean user-friendly interface using Gradio
- Encoded categorical features and scaled numerical data
- Supports direct deployment as a web app

---

## 🧠 Machine Learning Details

- **Algorithm**: Random Forest Classifier  
- **Dataset**: Open and Download the "**Fertilizer Prediction.csv**" from my repository and use it as the dataset  
- **Output Fertilizers**:  
  - Urea  
  - DAP  
  - 14-35-14  
  - 28-28  
  - 17-17-17  
  - 20-20  
  - 10-26-26  

---

## 🗂️ Folder Structure

```
📁 Fertilizer-Recommender/
├── fertilizer.ipynb           # Main notebook
├── scaler.joblib              # Trained Scaler for inputs
├── fertilizer_model.joblib    # Trained model
├── Fertilizer Prediction.csv  # Dataset
├── README.md                  # Project overview
```

---

## 🛠️ How to Run

### Option 1: Run Locally

1. Clone the repository:
```bash
git clone https://github.com/your-username/fertilizer-recommender.git
cd fertilizer-recommender
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the Gradio app:
```bash
python app.py
```

### Option 2: Run in Google Colab

- Open [`fertilizer.ipynb`](fertilizer.ipynb) in Google Colab
- Run all cells to explore and test the model

---

## 📊 Sample Inputs

| Temperature | Humidity | Moisture | Soil Type | Crop Type | Nitrogen | Phosphorous | Potassium |
|-------------|----------|----------|-----------|-----------|----------|-------------|-----------|
| 25°C        | 0.65     | 0.80     | Sandy     | Paddy     | 5        | 3           | 10        |

> **Output**: Recommended Fertilizer: **Urea**

---

## 📌 To-Do

- [ ] Add deployment using Streamlit or Flask
- [ ] Add crop recommendation integration
- [ ] Improve model accuracy with more data

---

## 🧑‍💻 Author

- **Atmakuri Leela Naga Premchand**
- Final Year B.Tech Student, CSE.

---

