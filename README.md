# Restaurant_Review_Analysis
Generative AI ( Restaurant_Review_Analysis )

**Project Title:**

Sentiment Analysis of Restaurant Reviews Using Natural Language Processing.

**Objective:**

To build a machine learning model that can classify restaurant reviews as positive or negative based on customer feedback. This sentiment classification will help restaurants understand customer satisfaction, improve service, and make data-driven business decisions.

**Approach (Python Workflow):**

**1. Data Loading & Exploration**
   
•	Imported and examined the dataset containing text reviews and their corresponding labels (positive or negative sentiment).

•	Identified imbalance or inconsistencies in the dataset (if any).

**2. Text Preprocessing (NLP)**
   
Performed standard NLP cleaning steps:

**3. Feature Extraction**
   
•	Used Bag of Words (CountVectorizer) or TF-IDF to convert text data into numerical vectors for modeling.

**4. Model Building**
   
•	Target variable: y = dataset['Liked'] (binary: 0 for negative, 1 for positive).

•	Models tested:

  - Naive Bayes

  - Logistic Regression

  - SVM (Support Vector Machine)

•	Evaluated using accuracy, precision, recall, and confusion matrix.

**5. Model Evaluation**
    
•	Calculated-

   -	Accuracy (e.g., ~80–85%)

   -	Confusion matrix to evaluate true positives and false positives

•	Selected the best-performing model for deployment or integration.
