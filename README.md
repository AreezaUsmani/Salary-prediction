# Salary-prediction
This project aims to predict an individual’s salary based on their years of professional experience using a supervised machine learning model. It leverages a Linear Regression algorithm to learn the relationship between experience and salary from historical data
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Salary Prediction using Ensemble Learning</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      line-height: 1.6;
      margin: 20px;
      color: #333;
    }
    h1, h2 {
      color: #2c3e50;
    }
    code {
      background: #f4f4f4;
      padding: 2px 6px;
      border-radius: 4px;
      font-family: monospace;
    }
    pre {
      background: #f4f4f4;
      padding: 10px;
      border-left: 4px solid #3498db;
      overflow-x: auto;
    }
    ul {
      list-style-type: square;
      margin-left: 20px;
    }
    .tag {
      display: inline-block;
      background: #3498db;
      color: white;
      padding: 3px 8px;
      border-radius: 5px;
      margin-right: 5px;
      font-size: 0.85em;
    }
  </style>
</head>
<body>

  <h1>💼 Salary Prediction using Ensemble Learning</h1>

  <p>
    This is a Streamlit-powered web app that predicts salaries based on a user’s <strong>Years of Experience</strong>. It uses ensemble models like
    <span class="tag">Linear Regression</span>, and
    <span class="tag">Bagging Classifier</span>
    for high-accuracy predictions.
  </p>

  <h2>📊 Dataset</h2>
  <p>The dataset <code>salary.csv</code> contains:</p>
  <ul>
    <li><code>YearsExperience</code>: Numeric input</li>
    <li><code>Salary</code>: Output target (numeric)</li>
  </ul>
  <pre>
YearsExperience,Salary
1.1,39343.00
2.0,43525.00
  </pre>

  <h2>🧠 Models Used</h2>
  <ul>
    <li>Linear Regression ✅</li>
    <li>Bagging Classifier ✅</li>
  </ul>

  <h2>🖥 App Features</h2>
  <ul>
    <li>🔢 Enter years of experience to predict salary</li>
    <li>📈 Real-time predictions with UI</li>
    <li>📉 Visualized model performance</li>
    <li>🎛 Built with Streamlit</li>
  </ul>

  <h2>🛠 Installation</h2>
  <pre>
git clone https://github.com/your-username/salary-prediction-ml.git
cd salary-prediction-ml
pip install -r requirements.txt
streamlit run app.py
  </pre>

  <h2>📦 Requirements</h2>
  <pre>
streamlit
pandas
scikit-learn
matplotlib
  </pre>

  <h2>🧪 Sample Usage</h2>
  <ul>
    <li><strong>Input:</strong> 4.5 years</li>
    <li><strong>Output:</strong> ₹72,000 (predicted salary)</li>
  </ul>

  <h2>📁 File Structure</h2>
  <pre>
salary-prediction/
│
├── salary.csv  
├── code for salaryprediction.ipynb
├── app.py               # Streamlit interface
├── Linearmodel.py             # ML code
├── requirements.txt     # Dependencies
└── README.md            # Documentation
  </pre>

  <h2>👤 Author</h2>
  <p><strong>Areeza Usmani</strong></p>

</body>
</html>
