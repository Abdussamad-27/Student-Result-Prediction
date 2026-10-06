# 🎓 Student Result Prediction System

A machine learning web application that predicts whether a student is likely to **Pass or Fail** based on their **study hours, attendance, and previous marks**.

The project uses **Gaussian Naive Bayes** for prediction and **Flask** to build the web application.

## 🚀 Features

- Predicts student result as **Pass/Fail**
- Uses **Gaussian Naive Bayes**
- Simple Flask web interface
- Takes study hours, attendance, and previous marks as input
- Displays prediction results instantly
- Model saved using Pickle

## 🛠️ Technologies Used

- Python
- Flask
- Pandas
- Scikit-learn
- HTML
- CSS
- Pickle

## 📊 Input Features

| Feature | Description |
|---|---|
| Study Hours | Hours studied per day |
| Attendance | Attendance percentage |
| Previous Marks | Previous examination marks |

**Target:** `Pass` or `Fail`

## 📂 Project Structure

```text
Student-Result-Prediction/
│
├── app.py
├── train_model.py
├── student_data.csv
├── model.pkl
│
├── templates/
│   ├── index.html
│   └── result.html
│
└── static/
    └── style.css
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
```

### 2. Open the project folder

```bash
cd Student-Result-Prediction
```

### 3. Install dependencies

```bash
pip install flask pandas scikit-learn
```

## 🧠 Train the Model

```bash
python train_model.py
```

This generates the trained `model.pkl` file.

## ▶️ Run the Application

```bash
python app.py
```

Open:

```text
http://127.0.0.1:5000
```

## 🔄 How It Works

```text
Student Input
     ↓
Study Hours + Attendance + Previous Marks
     ↓
Gaussian Naive Bayes
     ↓
Prediction
     ↓
Pass / Fail
```

## 📚 Dataset

The project uses `student_data.csv` with these columns:

```text
study_hours
attendance
previous_marks
result
```

## 🎯 Learning Outcomes

- Preparing a dataset for machine learning
- Selecting features and target variables
- Label encoding
- Train-test splitting
- Training a Naive Bayes model
- Evaluating model accuracy
- Saving a trained model using Pickle
- Loading an ML model into Flask
- Integrating machine learning with a web application

## 🔮 Future Improvements

- Use a larger real-world dataset
- Compare multiple ML algorithms
- Improve prediction accuracy
- Add data visualization
- Add a database
- Improve the UI
- Deploy the application online

## 👥 Contributors

**Your Name** – Machine Learning & Flask Development

**Friend 1** – Project contribution

**Friend 2** – Project contribution

> Replace the contributor names and contributions with your actual team details.

## 📄 License

This project is created for **educational and learning purposes**.

---

⭐ If you found this project useful, consider giving the repository a star!
