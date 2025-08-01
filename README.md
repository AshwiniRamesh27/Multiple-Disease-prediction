# Multiple-Disease-prediction
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Multiple Disease Prediction Pipeline</title>
</head>
<body>

  <h1>🩺 Multiple Disease Prediction Pipeline</h1>

  <p>
    A robust machine learning pipeline to predict multiple diseases using supervised learning models.
    It includes preprocessing, hyperparameter tuning, evaluation, and model saving for scalable healthcare applications.
  </p>

  <h2>📌 Overview</h2>
  <p>
    This project focuses on predicting the likelihood of multiple diseases using clinical or health-related data.
    It leverages powerful machine learning models with systematic tuning and evaluation for high predictive performance.
  </p>

  <h2>🧠 Models Used</h2>
  <ul>
    <li>Logistic Regression</li>
    <li>K-Nearest Neighbors (KNN)</li>
    <li>Random Forest</li>
    <li>XGBoost</li>
  </ul>
  <p>Each model is trained and tuned to find the best parameters and maximize the <strong>ROC-AUC</strong> score.</p>

  <h2>🔁 Workflow</h2>
  <ol>
    <li>
      <strong>Data Preparation:</strong> Input data is scaled and split into training and test sets. Supports imbalanced data via class weighting and parameter tuning.
    </li>
    <li>
      <strong>Hyperparameter Tuning:</strong> GridSearchCV (for small spaces) and RandomizedSearchCV (for large spaces like XGBoost) with Stratified K-Fold CV.
    </li>
    <li>
      <strong>Evaluation Metrics:</strong> Accuracy, Precision, Recall, F1-score, ROC-AUC, Confusion Matrix, and Classification Report.
    </li>
    <li>
      <strong>Model Selection:</strong> Best model chosen based on test ROC-AUC.
    </li>
    <li>
      <strong>Model Saving:</strong> Best model saved using <code>pickle</code> for future use.
    </li>
  </ol>

  <h2>📦 Dependencies</h2>
  <pre><code>pip install scikit-learn xgboost numpy</code></pre>

  <h2>🚀 Run the Project</h2>
  <pre><code>python disease_prediction_pipeline.py</code></pre>

  <h2>📁 Output</h2>
  <ul>
    <li>Trained model: <code>best_model_parkinsons.pkl</code></li>
    <li>Printed evaluation metrics for all models</li>
  </ul>

  <h2>💡 Use Case</h2>
  <p>
    Ideal for healthcare professionals and researchers to automate disease screening using predictive analytics.
  </p>

  <h2>📧 Contact</h2>
  <p>
    <strong>Your Name</strong><br>
    📧 youremail@example.com<br>
    🔗 <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
  </p>

</body>
</html>
