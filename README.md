# 🚦 Traffic Insight Pro  
### Predict Traffic Accident Severity using Machine Learning & Power BI

**Traffic Insight Pro** is an interactive web application built as part of our B.Tech CSE–DS Technical Seminar (PROJ-CSD681). The tool predicts the **severity level of a traffic accident** based on key parameters and provides insights via a Power BI dashboard.

---

## 📌 Features

- 🧠 Predicts **Accident Occurrence** and **Severity Level** (Low / Moderate / High)
- 📈 Integrated **Power BI Dashboard (.pbix)** for analytical insights
- 🌐 Interactive UI with form inputs and result modal
- 🔐 Machine learning powered backend using **Random Forest Classifier**
- ⚡ Built with **Flask**, **HTML/CSS**, and **JavaScript**

---

## 🧰 Tech Stack

| Technology     | Purpose                      |
|----------------|------------------------------|
| Python         | Backend, ML model training   |
| Flask          | Web framework (API & server) |
| scikit-learn   | Machine Learning (RF Model)  |
| HTML/CSS/JS    | Frontend Interface           |
| Power BI       | Data Visualization           |
| Git/GitHub     | Version Control & Hosting    |

---

## 📁 Project Structure

```

project-root/
│
├── app.py                          # Flask backend
├── train\_model.py                 # Model training script
├── traffic\_accident\_prediction.csv  # Dataset used
├── static/
│   ├── style.css                  # Frontend styling
│   ├── app.js                     # JS for modal and prediction
│   └── powerbi\_dashboard.jpg      # (optional) Dashboard image preview
│
├── templates/
│   └── dashboard.html             # Frontend template
│
├── model.pkl                      # Trained Random Forest model
├── encoders.pkl                   # Encoders for categorical features
├── target\_encoder.pkl             # Encoder for the target column
├── requirements.txt               # Python dependencies
├── Traffic Accident Analysis.pbix # Power BI Dashboard
└── README.md                      # You're reading it!

````

---

## 🧪 How to Run the App Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AbhraneelBose04/traffic-accident-predictor.git
   cd traffic-accident-predictor
````

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Flask app:**

   ```bash
   python app.py
   ```

4. Open your browser at: `http://127.0.0.1:5000`

---

## 📊 Power BI Dashboard

* File: `Traffic Accident Analysis.pbix`
* Open with Microsoft Power BI Desktop for interactive insights

---

## 👥 Team Members

| Name                | Roll No.       |
| ------------------- | -------------- |
| Abhraneel Bose      | BWU/BTD/22/342 |
| Harsha Nandi        | BWU/BTD/22/001 |
| Oindrila Khawas     | BWU/BTD/22/003 |
| Himani Das Talukder | BWU/BTD/22/047 |

---

## 📌 Acknowledgements

* **Brainware University** – Department of Computer Science & Engineering
* Course: **Technical Seminar with Modern Tool Application** (PROJ-CSD681)

---

## 📜 License

This project is part of an academic submission and is intended for educational purposes only.