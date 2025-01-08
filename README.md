<h1>Heart Disease Prediction using Logistic and Linear Regression</h1>

<h2>Dataset</h2>
<p>The dataset used is the <strong>Heart Disease dataset</strong> from <strong>sklearn.datasets</strong>.
  It includes various medical attributes such as age, sex, chest pain type, blood pressure, cholesterol levels, etc., that are used to predict the presence of heart disease in a patient. 
  But only took 2 of the features
  The target variable is a binary classification label indicating whether the patient has heart disease (1) or not (0), as well as a regression target variable.</p>

<h2>Modules Used</h2>
<ul>
    <li><strong>sklearn.datasets</strong>: To load the Heart Disease dataset.</li>
    <li><strong>sklearn.model_selection</strong>: For splitting the dataset into training and testing sets using <code>train_test_split</code>.</li>
    <li><strong>sklearn.preprocessing</strong>: For scaling the feature data using <code>StandardScaler</code> (optional but recommended for Logistic Regression).</li>
    <li><strong>sklearn.linear_model</strong>: To apply both Logistic Regression and Linear Regression using <code>LogisticRegression</code> and <code>LinearRegression</code>.</li>
    <li><strong>sklearn.metrics</strong>: For evaluating model performance using accuracy, confusion matrix, and other regression metrics.</li>
    <li><strong>matplotlib.pyplot</strong>: For plotting model performance visualizations such as scatter plots and confusion matrices.</li>
</ul>

<h2>Process</h2>
<p>The dataset is loaded and split into training and testing sets using <strong>train_test_split</strong>. 
  For Logistic Regression, the features are standardized using <strong>StandardScaler</strong>, and a model is trained to predict heart disease (binary classification). 
  For Linear Regression, the same dataset is used to predict continuous heart disease values (regression). 
  The models are evaluated based on accuracy for Logistic Regression and mean squared error for Linear Regression. 
  Both models' performances are plotted for visualization.</p>

<h2>Output</h2>
<p>The output includes the accuracy score for Logistic Regression and the predicted values for Linear Regression, as well as visualizations 
  of model performance, such as scatter plots comparing true vs. predicted labels and confusion matrix plots for the classification task.</p>
