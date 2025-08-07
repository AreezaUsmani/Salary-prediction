# Salary-prediction
  <h1>💼 Salary Prediction using Ensemble Learning</h1>

  <p>
    This is a Streamlit-powered web app that predicts salaries based on a user’s <strong>Years of Experience</strong>. It uses ensemble models like
    <span class="tag">Random Forest</span>,
    <span class="tag">Gradient Boosting</span>, and
    <span class="tag">Bagging Regressor</span>
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
    <li>Random Forest Regressor ✅</li>
    <li>Gradient Boosting Regressor ✅</li>
    <li>Bagging Regressor ✅</li>
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

  <h2>🖼 Output Example</h2>
  <p>Here’s how the prediction looks in the app:</p>
  <img src="<img width="1886" height="966" alt="output" src="https://github.com/user-attachments/assets/bbb48375-dc78-4be4-b971-fdb6c9cd9f1a" />
" alt="Salary Prediction Output Example">

  <h2>📁 File Structure</h2>
  <pre>
salary-prediction/
│
├── salary.csv           # Dataset
├── app.py               # Streamlit interface
├── model.py             # ML code
├── output.png           # Output screenshot
├── requirements.txt     # Dependencies
└── README.html          # Documentation
  </pre>

  <h2>👤 Author</h2>
  <p><strong>Areeza Usmani</strong></p>

  <h2>📃 License</h2>
  <p>This project is licensed under the <strong>MIT License</strong>.</p>

</body>
</html>
