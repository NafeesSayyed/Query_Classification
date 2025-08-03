# Query_Classification
This is my First ML based project for classifying short text queries into predefined domains using scikit-learn.
<br>
Author - Nafees Sayyed
 Problem Statement
Given a dataset of short English text queries and their corresponding domain labels, build a model that can classify new/unseen queries into the appropriate category.

 Dataset
Format: CSV

Total Rows: ~3800

Features:

Query: A short user query in text format.

Domain: Category label (e.g., Career, Tools, Techniques, etc.)

Characteristics: Includes missing values and class imbalance for preprocessing practice.

 Tech Stack
Language: Python

Libraries: Pandas, Scikit-learn, Matplotlib, Seaborn

Model(s): Logistic Regression

Text Vectorization: TfidfVectorizer

 Data Preprocessing
Removed null values

Cleaned text (lowercased, removed special characters)

Encoded labels

Applied CountVectorizer to convert text to numerical form

Handled class imbalance


 Model Building
Split data into train/test sets

Trained classification model

Evaluated using metrics like Accuracy, Precision, Recall, F1-Score

Used classification report

 Visualizations
Class distribution plot using Matplotlib and Seaborn

 Results
Best Model: Logistic Regression

Accuracy: 67.14%

Model performs well on majority classes, struggles slightly on underrepresented ones
