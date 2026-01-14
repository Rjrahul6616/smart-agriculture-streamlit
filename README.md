# 🌾 Smart Agriculture Monitoring System using Streamlit

## 📌 Description
The Smart Agriculture Monitoring System is a Python-based application that simulates IoT sensor data and visualizes it in real time using a Streamlit dashboard. The system monitors important agricultural parameters such as temperature and soil moisture, helping in smart decision-making for farming.

This project demonstrates the practical use of IoT concepts, local data processing, and real-time visualization .

---

## 🎯 Objectives
- Simulate real-time agricultural sensor data
- Process sensor data and generate alerts
- Visualize live temperature and moisture data
- Demonstrate smart agriculture concepts using Streamlit

---

## 🧩 System Workflow
1. IoT Device Simulator generates temperature and moisture data  
2. Local Processing Function analyzes data and raises alerts  
3. Streamlit Dashboard displays live sensor data  

---

## 📁 Project Structure

```text
smart-agriculture-streamlit/
│
├── dashboard.py
├── device_simulator.py
├── local_function.py
├── requirements.txt
├── README.md
├── .gitignore
│
└── data/
    ├── processed_data.json
    └── iot_messages.json
```

---

## ⚙️ Technologies Used
- Python
- Streamlit
- Pandas
- IoT Simulation
- JSON

---

## 📥 Installation
Make sure Python is installed, then run:
```bash
pip install -r requirements.txt


▶️ How to Run the Project

Step 1: Run IoT Device Simulator
python device_simulator.py

Step 2: Run Data Processing Function
python local_function.py

Step 3: Run Streamlit Dashboard
streamlit run dashboard.py

Open your browser and go to:
http://localhost:8501
```
---

## 📊 Dashboard Features

Live temperature and soil moisture visualization.

Auto-refresh dashboard.

Simple and interactive interface.

---

## 🚨 Alerts

🔥 High Temperature Alert when temperature exceeds 35°C.

💧 Low Moisture Alert when moisture drops below 30%.

Alerts are displayed in the terminal.

## 🎓 Use Case

Smart Agriculture demonstration.

IoT and data visualization learning.

---
## 🔮 Future Enhancements

Integration with real IoT sensors.

Cloud database support.

Mobile or SMS alerts.

Crop recommendation using machine learning.

## 👨‍💻 Author

Your Name : Rahul Bhati. 

Department of Computer Science / Engineering .

College Name : MIT-ADT , PUNE .

