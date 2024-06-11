
<h1>Credit Card Fraud Detection</h1>

<h2>Introduction</h2>
<p>
    This project aims to detect fraudulent credit card transactions using machine learning techniques. 
    The dataset used in this project is highly imbalanced, with a majority of transactions being legitimate 
    and a small fraction being fraudulent. We'll build and evaluate various models to predict fraudulent 
    transactions based on the given features.
</p>

<h2>Dataset</h2>
<p>
    The dataset used in this project contains the following columns:
</p>
<ul>
    <li><strong>Time</strong>: Number of seconds elapsed between this transaction and the first transaction in the dataset.</li>
    <li><strong>V1, V2, ..., V28</strong>: Result of a PCA Dimensionality reduction to protect user identities and sensitive features.</li>
    <li><strong>Amount</strong>: Transaction amount.</li>
    <li><strong>Class</strong>: The response variable, 1 means fraudulent transaction, 0 means legitimate transaction.</li>
</ul>

<h2>Requirements</h2>
<ul>
    <li>Python 3.x</li>
    <li>pandas</li>
    <li>numpy</li>
    <li>matplotlib</li>
    <li>seaborn</li>
    <li>scikit-learn</li>
    <li>imbalanced-learn (for handling imbalanced data)</li>
</ul>

<h2>Usage</h2>
<ol>
    <li><strong>Clone this repository to your local machine.</strong></li>
    <pre><code>git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection</code></pre>
    <li><strong>Install the required libraries.</strong></li>
    <pre><code>pip install -r requirements.txt</code></pre>
    <li><strong>Download the dataset from Kaggle and place it in the project directory.</strong></li>
    <li><strong>Run the Jupyter Notebook to train the model and make predictions.</strong></li>
    <pre><code>jupyter notebook Credit\ Card\ Fraud\ Detection.ipynb</code></pre>
    <p>You can also run the Python script to execute the code directly.</p>
    <pre><code>credit_card_fraud_detection.py</code></pre>
    <li><strong>Modify the script or notebook to experiment with different machine learning algorithms, feature engineering techniques, etc.</strong></li>
</ol>

<h2>Results</h2>
<p>
    The performance of the models is evaluated using various metrics such as accuracy, precision, recall, F1-score, 
    and the area under the ROC curve (AUC).
</p>



