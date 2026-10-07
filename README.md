# EduPredict — Student Performance Prediction Dashboard

EduPredict is a Machine Learning-based web application that predicts student performance using **Flask, Random Forest, and an interactive dashboard**.

## 🚀 Features

* Single Student Prediction
* Batch CSV Prediction
* Feature Importance Visualization
* Prediction Probability Charts
* Personalized Suggestions
* REST API Support

## 🛠️ Tech Stack

* Python
* Flask
* Scikit-learn
* Pandas
* NumPy
* HTML, CSS, JavaScript
* Chart.js
* Git & GitHub

## 📊 Prediction Classes

* At Risk
* Average
* Good
* Excellent

## 📁 Project Structure

```text
EduPredict/
├── app.py
├── train_model.py
├── predict.py
├── requirements.txt
├── dataset/
├── model/
├── templates/
├── static/
├── uploads/
└── utils/
```

## ⚙️ Setup

Clone the repository:

```bash
git clone https://github.com/your-username/EduPredict.git
cd EduPredict
```

Create and activate a virtual environment:

```bash
python -m venv .venv
.venv\Scripts\activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## 🧠 Train the Model

Before running the application, train the Random Forest model:

```bash
python train_model.py
```

This will train the model using the dataset and save the trained model inside the `model/` directory.

## ▶️ Run the Application

Start the Flask application:

```bash
python app.py
```

The application will run locally at:

```text
http://127.0.0.1:5000
```

Open the URL in your browser to access the EduPredict dashboard.

## 🔮 Prediction Workflow

1. Enter the student's academic information.
2. Submit the prediction form.
3. The trained Random Forest model processes the input.
4. EduPredict predicts one of four performance classes:

   * At Risk
   * Average
   * Good
   * Excellent
5. The dashboard displays the prediction probability.
6. Personalized suggestions are provided based on the predicted performance.

## 📂 Batch Prediction

EduPredict also supports prediction for multiple students using a CSV file.

Upload a CSV file through the dashboard, and the application will generate predictions for all students.

## 📊 Feature Importance

The dashboard provides a visualization of the most important features used by the Random Forest model for making predictions.

This helps understand which student-related factors have the greatest influence on the prediction.

## 🔌 REST API

EduPredict provides REST API support for making predictions programmatically.

The API can be integrated with other applications or services that need student performance predictions.

## 🧪 Model

The application uses a **Random Forest Classifier** from Scikit-learn.

The model classifies students into four performance categories:

| Class     | Description                                      |
| --------- | ------------------------------------------------ |
| At Risk   | Student may require significant academic support |
| Average   | Student is performing at an average level        |
| Good      | Student is performing well                       |
| Excellent | Student is performing at a high level            |

## 📌 Future Enhancements

* User authentication and role-based access
* Database integration
* Cloud deployment
* Advanced model comparison
* Student performance history
* Automated email notifications
* Explainable AI-based predictions

## 👨‍💻 Author

**Sahil Pawar**

Computer Engineering Student
Pimpri Chinchwad College of Engineering (PCCOE)

---

⭐ If you find this project useful, consider giving the repository a star!
