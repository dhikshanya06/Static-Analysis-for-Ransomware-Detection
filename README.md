# Static-Analysis-for-Ransomware-Detection
  <h1>🛡️ Static Analysis for Ransomware Detection</h1>

  <p>This project aims to detect ransomware using <strong>static analysis</strong> and <strong>machine learning</strong>. It analyzes executable (.exe) files without running them, extracts useful features, and predicts whether they are <em>benign</em> or <em>malicious</em>.</p>

  <h2>🔧 Features</h2>
  <ul>
    <li>Extracts static features from executable files</li>
    <li>Trains machine learning models to classify files</li>
    <li>Shows accuracy, precision, recall, and F1-score</li>
  </ul>

  <h2>🛠️ Technologies Used</h2>
  <ul>
    <li>Python 3</li>
    <li>Scikit-learn (for ML models)</li>
    <li>Pandas and NumPy (for data processing)</li>
  </ul>

  <h2>📂 How to Run</h2>
  <ol>
    <li>Clone this repository:<br>
      <code>git clone https://github.com/dhikshanya06/Static-Analysis-for-Ransomware-Detection.git</code>
    </li>
    <li>Install required libraries:<br>
      <code>pip install -r requirements.txt</code>
    </li>
    <li>Train the model:<br>
      <code>python train_model.py</code>
    </li>
    <li>Test with a new file:<br>
      <code>python predict.py your_file.exe</code>
    </li>
  </ol>

  <h2>📌 Note</h2>
  <p>This project uses <strong>static analysis only</strong>. It does not run the malware, making it safer for testing.</p>
