<h1>🌸 Iris Flower Classification using Decision Trees</h1>

<p>
  A machine learning project that applies <b>Decision Tree Classification</b> on the classic Iris dataset. 
  The model classifies iris flowers based on petal features and includes decision tree visualization, 
  decision boundaries, evaluation metrics, and cross-validation analysis.
</p>

<hr/>

<h2>📊 Project Overview</h2>
<ul>
  <li>Dataset: <code>sklearn.datasets.load_iris()</code></li>
  <li>Features used: Petal length & Petal width</li>
  <li>Model: Decision Tree Classifier (max_depth=3)</li>
  <li>Visualizations:
    <ul>
      <li>Decision Tree structure</li>
      <li>Decision boundaries of classification</li>
      <li>Confusion Matrix (Heatmap)</li>
    </ul>
  </li>
  <li>Evaluation:
    <ul>
      <li>Accuracy Score</li>
      <li>Classification Report</li>
      <li>5-Fold Cross-Validation</li>
    </ul>
  </li>
</ul>

<hr/>

<h2>⚙️ Installation & Setup</h2>
<pre>
# Clone this repository
git clone https://github.com/your-username/iris-decision-tree.git
cd iris-decision-tree

# Install dependencies
pip install -r requirements.txt
</pre>

<h3>Requirements:</h3>
<ul>
  <li>Python 3.8+</li>
  <li>scikit-learn</li>
  <li>matplotlib</li>
  <li>seaborn</li>
  <li>numpy</li>
</ul>

<hr/>

<h2>🚀 How to Run</h2>
<pre>
python iris_decision_tree.py
</pre>

<hr/>

<h2>📈 Results</h2>
<ul>
  <li>Decision Tree visualized using <code>plot_tree</code>.</li>
  <li>Decision boundaries show class separability in feature space.</li>
  <li>Confusion Matrix highlights correct vs misclassified samples.</li>
  <li>Cross-validation provides robust performance estimation.</li>
</ul>

<hr/>

<h2>📷 Sample Outputs</h2>
<p>
  <b>Decision Tree Visualization:</b><br/>
  <img src="assets/decision_tree.png" width="500"/>
</p>

<p>
  <b>Decision Boundaries:</b><br/>
  <img src="assets/decision_boundaries.png" width="500"/>
</p>

<p>
  <b>Confusion Matrix:</b><br/>
  <img src="assets/confusion_matrix.png" width="400"/>
</p>

<hr/>


.
