# 🎓 Student Performance Indicator

A complete end-to-end machine learning project to analyze and predict student performance based on various demographic and academic features. This project includes:

* Exploratory Data Analysis (EDA)
* Model Training and Evaluation
* Web Application Deployment using Flask


## 📂 Project Structure

* ├── app.py                        # Flask application entry point
* ├── requirements.txt              # Python dependencies
* ├── setup.py                      # Package configuration
* ├── .gitignore                    # Files to ignore in Git
* ├── notebooks/
* │   ├── 1. EDA STUDENT PERFORMANCE.ipynb
* │   └── 2. MODEL TRAINING.ipynb
* ├── src/
* │   ├── pipeline/
* │   │   ├── predict_pipeline.py   # Prediction pipeline
* │   │   └── ...                   # Other ML utilities
* ├── templates/
* │   ├── index.html                # Landing page
* │   └── home.html                 # Prediction form/results


## 🎯 Objective

To predict student exam performance using input features such as gender, parental education, test preparation, etc. This can help identify students at risk and provide targeted interventions.


## 🔍 Features

* 🔢 Accepts input scores and student information
* 🤖 Uses trained ML models (e.g., Random Forest, CatBoost)
* 📊 Displays predicted output on a clean web interface
* 🧠 Scikit-learn & Boosting model support
* 🌐 Flask web interface for live interaction


## 🛠️ Tech Stack

* **Frontend:** HTML
* **Backend:** Python, Flask
* **ML Libraries:** Scikit-learn, XGBoost, CatBoost, Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn


## 📦 Installation

1. **Clone the repo**

   git clone https://github.com/yourusername/student-performance-indicator.git
   cd student-performance-indicator

2. **Create a virtual environment**

   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3. **Install dependencies**

   pip install -r requirements.txt

4. **Run the app**

   python app.py

5. Open your browser at: `http://localhost:5000/`


## 📈 Example Input

* Gender: Male
* Race/Ethnicity: Group B
* Parental Education: Bachelor's degree
* Lunch: Standard
* Test Prep: Completed
* Reading Score: 72
* Writing Score: 74


## 🙋‍♂️ Author

**Vihaan Malik**