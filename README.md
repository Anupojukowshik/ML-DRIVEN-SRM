# Machine Learning-Driven Fault Detection in Switched Reluctance Motor (SRM)

## 📌 Project Description

This project presents a Machine Learning-based fault detection system for a Switched Reluctance Motor (SRM). The motor is designed and simulated using ANSYS Maxwell (RMxprt & Maxwell 2D), and motor performance data is collected under both normal and faulty operating conditions.

The collected data is used to train a Random Forest machine learning model that can automatically identify motor faults. This approach helps improve predictive maintenance, reduce downtime, and increase the reliability of SRMs.

---

# 🎯 Problem Statement

Although Switched Reluctance Motors (SRMs) are highly efficient, simple in construction, and fault tolerant, they are still affected by faults such as:

- Rotor Eccentricity
- Winding Faults
- Bearing Faults
- Converter Faults

Traditional fault detection methods require manual inspection and periodic maintenance, which are time-consuming and may fail to detect faults at an early stage.

This project solves this problem by using Machine Learning to automatically classify normal and faulty motor conditions using simulation data.

---

# 🎯 Objectives

- Design a Switched Reluctance Motor (SRM).
- Simulate normal and faulty operating conditions.
- Generate motor performance data using FEM simulation.
- Build a dataset from simulation results.
- Train a Random Forest classifier.
- Predict motor faults automatically.

---

# ⚙️ Software Used

- Python
- Jupyter Notebook
- ANSYS Electronics Desktop
- ANSYS Maxwell
- RMxprt

---

# 📚 Python Libraries Used

- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

# 🔧 Machine Learning Algorithm

**Random Forest**

Random Forest was selected because it provides:

- High Accuracy
- Fast Prediction
- Low Overfitting
- Good Performance on Classification Problems

---

# 📊 Input Features

The machine learning model uses the following motor parameters:

- Torque
- Winding Current

---

# 🔄 Project Workflow

```
SRM Design
      │
      ▼
FEM Simulation
      │
      ▼
Generate Normal & Fault Data
      │
      ▼
Dataset Preparation
      │
      ▼
Data Preprocessing
      │
      ▼
Train Random Forest Model
      │
      ▼
Fault Prediction
```

---

# ✅ Features

- Automatic Fault Detection
- Machine Learning-Based Classification
- Simulation-Based Dataset Generation
- Early Fault Identification
- Predictive Maintenance

---

# 🎯 Applications

- Electric Vehicles
- Industrial Automation
- Smart Manufacturing
- Condition Monitoring
- Predictive Maintenance

---

# 📂 Project Files

```
README.md
Project_Report.pdf
SRM_Fault_Detection.ipynb
SRM_Dataset.csv
requirements.txt
```

---

# 🚀 Future Scope

- Real-Time Fault Detection
- IoT-Based Monitoring
- Deep Learning Models
- Cloud-Based Predictive Maintenance
- Embedded System Deployment

---

# 👨‍💻 Author

**Anupoju Kowshik**

Bachelor of Technology (Electrical & Electronics Engineering)

Velagapudi Ramakrishna Siddhartha Engineering College