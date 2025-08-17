<!-- README.md (HTML version) -->

<h1>CardioSight: Coronary Heart Disease Prognosis and Diagnosis using Machine Learning</h1>

<p>
  <strong>CardioSight</strong> aims to improve coronary heart disease (CHD) prognosis and diagnosis using
  machine learning by integrating both <em>physical health indicators</em> (cholesterol, blood pressure, heart rate)
  and <em>psychological factors</em> (stress levels, sleep quality).
</p>

<p>
  Unlike traditional CHD prediction models that rely solely on physical metrics, CardioSight introduces a
  <strong>holistic approach</strong> by combining two different datasets:
</p>

<ul>
  <li><strong>UCI Heart Disease Dataset</strong> (physical health factors)</li>
  <li><strong>Psychological &amp; Sleep Health Dataset</strong> (stress and lifestyle indicators)</li>
</ul>

<p>
  By merging these domains, the project enhances predictive performance and enables <strong>early intervention</strong>
  for at-risk individuals.
</p>

<hr />

<h2>🚀 Key Features</h2>
<ul>
  <li><strong>Dataset Integration:</strong> Combines physical health data with psychological and lifestyle data to create a more comprehensive risk profile.</li>
  <li><strong>Ensemble Learning:</strong> Uses Random Forest, XGBoost, and ensemble averaging for robust prediction.</li>
  <li><strong>Performance Metrics:</strong> Evaluated using Accuracy, Precision, Recall, F1-Score, and ROC–AUC, highlighting strong generalization.</li>
  <li><strong>Visualization:</strong> Includes scatter plots (Actual vs Predicted) to clearly demonstrate model performance.</li>
</ul>

<hr />

<h2>📊 Methodology</h2>

<h3>1) Data Preprocessing</h3>
<ul>
  <li>Cleaning, handling missing values, and normalization/standardization.</li>
  <li>Feature engineering across both datasets.</li>
</ul>

<h3>2) Dataset Combination</h3>
<ul>
  <li>Aligning common features such as <em>age</em>, <em>gender</em>, and <em>blood pressure</em>.</li>
  <li>Integrating stress and lifestyle scores with clinical measurements.</li>
</ul>

<h3>3) Model Training</h3>
<ul>
  <li>Trained multiple models: Logistic Regression, Random Forest, XGBoost.</li>
  <li>Final predictions obtained using an <strong>ensemble approach</strong> for improved robustness.</li>
</ul>

<h3>4) Evaluation Metrics (Positive Outcomes)</h3>
<ul>
  <li><strong>Accuracy:</strong> High accuracy achieved with the ensemble model.</li>
  <li><strong>Precision &amp; Recall:</strong> Balanced results showing reliability in identifying true CHD cases.</li>
  <li><strong>F1-Score:</strong> Strong balance between false positives and false negatives.</li>
</ul>

<!-- Optional: quick metrics table (fill with your actual numbers) -->
<table>
  <thead>
    <tr>
      <th>Model</th>
      <th>Accuracy</th>
      <th>Precision</th>
      <th>Recall</th>
      <th>F1-Score</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Ensemble (Final)</strong></td>
      <td><strong>0.99</strong></td>
      <td><strong>1</strong></td>
      <td><strong>0.99</strong></td>
      <td><strong>0.99</strong></td>
    </tr>
  </tbody>
</table>

<hr />

<h2>📈 Results</h2>
<ul>
  <li>The <strong>Ensemble Model</strong> consistently outperformed individual classifiers.</li>
  <li>Integrating psychological and lifestyle factors improved <strong>Recall</strong>, capturing more at-risk patients than physical-only baselines.</li>
  <li>Scatter plots of <em>Actual vs Predicted TenYearCHD</em> demonstrate strong alignment.</li>
</ul>

<!-- Embed your plot (update the src path to your plot file) -->
<p align="center">
  <img src="assets/actual_vs_predicted_tenyearchd.png" alt="Actual vs Predicted TenYearCHD (Ensemble Model)" width="70%">
</p>

<hr />

<h2>🧑‍💻 Tech Stack</h2>
<ul>
  <li><strong>Languages:</strong> Python</li>
  <li><strong>Libraries:</strong> Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn</li>
  <li><strong>Models:</strong> Logistic Regression, Random Forest, XGBoost, Ensemble Learning</li>
</ul>

<hr />

<h2>📌 Conclusion</h2>
<p>
  CardioSight provides a <strong>comprehensive, reliable, and innovative</strong> approach to CHD prediction by
  combining medical and psychological insights. Results show that integrating <em>stress</em> and <em>sleep quality</em>
  factors with physical health indicators leads to <strong>higher predictive accuracy</strong> and
  <strong>better early detection</strong>—paving the way for personalized preventive care.
</p>

<!-- Optional: quick navigation -->
<p>
  <a href="#cardsight-coronary-heart-disease-prognosis-and-diagnosis-using-machine-learning">▲ Back to top</a>
</p>
