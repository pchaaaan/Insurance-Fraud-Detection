<h1>Insurance Fraud Detection</h1>

<p>This project focuses on detecting insurance fraud using machine learning models. I have utilized a dataset to predict fraudulent insurance claims leveraging various classifiers such as Decision Tree, Random Forest, and advanced techniques for hyperparameter tuning including RandomizedSearchCV and GridSearchCV.</p>

<h2>Project Overview</h2>

<ul>
  <li><strong>Data Preprocessing:</strong> Loaded the training and testing datasets, handling categorical variables using OneHotEncoding and performing data cleaning.</li>
  <li><strong>Exploratory Data Analysis (EDA):</strong> Visualized the distribution of the target variable (FRAUDFOUND) to understand the data imbalance and gain insights.</li>
  <li><strong>Model Building:</strong> Trained Decision Tree and Random Forest classifiers on the dataset.</li>
  <li><strong>Model Evaluation:</strong> Evaluated model performance using accuracy, precision, recall, and f1-score metrics along with confusion matrices.</li>
  <li><strong>Hyperparameter Tuning:</strong> Utilized RandomizedSearchCV and GridSearchCV to fine-tune model parameters for improved accuracy.</li>
</ul>

<h2>Technologies Used</h2>

<ul>
  <li>Python</li>
  <li>Pandas & NumPy for data manipulation</li>
  <li>Scikit-learn for model building and evaluation</li>
  <li>Seaborn & Matplotlib for data visualization</li>
  <li>OneHotEncoder for handling categorical variables</li>
</ul>

<h2>Models Implemented</h2>

<ul>
  <li>Decision Tree Classifier</li>
  <li>Random Forest Classifier</li>
</ul>

<h2>Hyperparameter Tuning Techniques</h2>

<ul>
  <li>RandomizedSearchCV</li>
  <li>GridSearchCV</li>
</ul>

<h2>Results</h2>

<p>The models were evaluated based on their accuracy on the test set, with the Random Forest Classifier showing a promising performance after hyperparameter tuning. The process demonstrated the importance of parameter tuning in enhancing model accuracy and overall prediction performance.</p>

<h2>Running the Project</h2>

<ol>
  <li>Clone the repository.</li>
  <li>Ensure Python and necessary libraries (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib) are installed.</li>
  <li>Run the Jupyter Notebook/Python script to train the models and make predictions.</li>
</ol>

<h2>Conclusion</h2>

<p>This project highlights the effectiveness of machine learning techniques in detecting fraudulent activities in insurance claims. By comparing different models and tuning their parameters, I achieved significant accuracy in predictions, demonstrating the potential of ML in automating fraud detection processes in the insurance industry.</p>
