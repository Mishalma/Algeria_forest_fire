# Algeria Forest Fire Prediction

## 🔥 Overview
Algeria Forest Fire Prediction is a machine learning-based project designed to predict and analyze the occurrence of forest fires in Algeria. The model utilizes climate, vegetation, and environmental data to assess fire risks and help authorities take preventive measures.

## 🚀 Features
- **Data Collection & Preprocessing**: Cleans and processes environmental and meteorological data.
- **Machine Learning Models**: Uses algorithms like Random Forest, Gradient Boosting, and Deep Learning models.
- **Prediction & Analysis**: Forecasts fire occurrence based on input features.
- **Visualization & Reports**: Generates visual reports for better decision-making.
- **Web Interface (Flask)**: Allows users to input data and get fire risk predictions.

## 📂 Project Structure
```
AlgeriaForestFire/
│── data/                # Dataset files
│── models/              # Trained machine learning models
│── static/              # CSS, JavaScript, images
│── templates/           # HTML templates (Flask views)
│── .venv/               # Virtual environment
│── main.py              # Flask application
│── requirements.txt     # Required Python packages
│── README.md            # Project documentation
```

## ⚙️ Installation
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Mishalma/Algeria_forest_fire.git
cd Algeria_forest_fire
```

### 2️⃣ Create a Virtual Environment
```bash
python3 -m venv .venv
source .venv/bin/activate  # On macOS/Linux
.venv\Scripts\activate     # On Windows
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Flask App
```bash
python main.py
```
Access the web interface at `http://127.0.0.1:5000/`.

## 📊 Dataset
The dataset includes environmental features such as:
- **Temperature** (°C)
- **Humidity** (%)
- **Wind Speed** (km/h)
- **Rainfall** (mm)
- **Vegetation Index**
- **Past Fire Incidents**

## 🧠 Machine Learning Models Used
- **Random Forest**
- **Gradient Boosting**
- **Neural Networks** (for deep learning)
- **SVM** (Support Vector Machines)

## 📈 Model Performance
Evaluation metrics used:
- **Accuracy**
- **Precision & Recall**
- **F1 Score**
- **ROC-AUC Curve**

## 🌍 Future Enhancements
- Expand dataset to include **satellite images**.
- Implement **real-time monitoring**.
- Improve model accuracy with **Transfer Learning**.
- Deploy on a **cloud platform** for accessibility.

## 🤝 Contributing
Want to contribute? Follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Added new feature"`).
4. Push to your branch (`git push origin feature-branch`).
5. Open a Pull Request!

## 📜 License
This project is licensed under the **MIT License**.

---
🔥 **Developed by Mishalma**
