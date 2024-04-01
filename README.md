# Netflix-Movies-And-TV-Shows-Clustering-final-Iteration



![Local GIF](venti-views-lI7dlA5VBp8-unsplash.jpg)
Photo by <a href="https://unsplash.com/@ventiviews?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Venti Views</a> on <a href="https://unsplash.com/photos/white-and-black-concrete-building-during-night-time-lI7dlA5VBp8?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
  
  

<h3 align="Left">
<br>
 <h2>Problem Statement</h1>

<br>
The dataset originates from an ongoing cardiovascular study involving residents of Framingham, Massachusetts. Its primary aim is to predict whether a patient faces a 10-year risk of developing coronary heart disease (CHD). Comprising over 4000 records and 15 attributes, each attribute represents a potential risk factor, encompassing demographic, behavioral, and medical aspects..<br>
<br>
<h2>Project Summary</h1>

  <br>
Tasked with analyzing a dataset from a cardiovascular study in Framingham, Massachusetts, comprising 3,390 rows and 17 features, my objective was to develop a model capable of predicting a patient's 10-year risk of coronary heart disease. Despite the absence of duplicate values, the dataset did contain some missing data in certain features, albeit at a manageable percentage. The features furnished valuable patient information, encompassing age, education, gender, smoking status, as well as health-related metrics such as cholesterol levels, diabetes status, blood pressure, BMI, glucose levels, and heart rate.<br>
<br>
  <br>
<h2>Project Steps</h1>

  <br>
1.  Data Preprocessing:
<br>
  <br>
 <ul>
 <li>Imputed missing values by employing median or mode imputation based on feature distributions. </li>
  <li>Categorized features into categorical, discrete, and continuous.</li>
  <li>Opted not to address outliers, considering the health-oriented nature of the problem and the dataset's scale.</li>
</ul>
  <br>
   <br>
2. Exploratory Data Analysis (EDA):
<br>
   <br>
   <ul>
  <li>Conducted comprehensive EDA, comprising univariate, bivariate, and multivariate analyses.</li>
  <li>Unearthed insights regarding gender and smoking prevalence, diabetes rates, hypertension prevalence, and age distributions.</li>
  <li>Identified correlations between features and their potential impact on CHD risk.</li>
</ul>
 <br>
   <br>
3. Feature Engineering:
<br>
   <br>
    <ul>
<li>Applied label encoding for categorical features.</li>
<li>Introduced novel features like pulse_pressure, smoking_status, and diabetic_status.</li>
<li>Calculated the Variance Inflation Factor (VIF) to gauge multicollinearity.</li>
<li>Selected pivotal features for further analysis.</li>
</ul>
  <br>
   <br>
4. Handling Imbalanced Data:
<br>
   <br>
   <ul>
<li>Mitigated dataset imbalance using SMOTE (Synthetic Minority Over-sampling Technique).</li>
    </ul>
  <br>
   <br>
5. Model Selection and Training:
<br>
   <br>
    <ul>
<li>Partitioned the data into training and testing subsets.</li>
<li>Trained diverse machine learning models, including Logistic Regression, K-Nearest Neighbors, Random Forest, Naive Bayes, and XGBoost.</li>
<li>Evaluated model performance using accuracy, precision, recall, F1-score, and AUC metrics.</li>
<li>Tuned hyperparameters via GridSearchCV.</li>
   </ul>  
  <br>
   <br>
<h2>Model Conclusion</h1>

   <br>
    <ul>
<li>Among all models, XGBoost emerged as the top performer.</li>
<li>Post extensive hyperparameter tuning, the XGBoost model achieved remarkable accuracy, recording 99% on the training set and 94% on the test set.</li>
<li>Key hyperparameters encompassed 'gamma': 0, 'learning_rate': 0.1, 'max_depth': 5, and 'n_estimators': 300.</li>
<li>The model accurately predicted 518 class 0 patients and 509 class 1 patients out of 1152 patients, with 90 false negatives and 35 false positives.</li>
</ul> 
</h3>
