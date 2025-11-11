# 🚴‍♂️ Cycling Load Predictor

A full-stack machine learning app to help cyclists manage their weekly training load. It predicts how many more kilometers a rider can safely add during the current week without risking performance drop or overtraining — using Training Stress Score logic and past ride data.

---

## 🧠 How It Works

1. Load your past ride data (CSV: date, distance, pace, elevation).
2. Train an ML model (Random Forest) to learn safe weekly load patterns.
3. Enter new ride details each week (km, pace, elevation).
4. App tells you your predicted limit and how much you can still ride this week.

---

## 📁 Project Structure


---

## 🚀 Setup Instructions

### 1. 📊 Prepare Your Dataset

Put your cycling activity file (`activities.csv`) in:


It should contain at least the following columns:

- `Activity Date`
- `Distance`
- `Elapsed Time`
- `Elevation Gain`

---

### 2. 🧠 Train the ML Model

```bash
cd ml_model
python train_model.py

✅ This will generate a model.pkl file and place it into: 
/backend/model.pkl

