# Email-Spam-Detection-Using-Logistic-Regression
## Project Overview:
This project aims to build a robust email spam detection system using machine learning techniques. The primary objective is to classify emails as spam or not spam with high accuracy. We achieved a 95% accuracy using a logistic regression model, enhanced with feature engineering and TF-IDF vectorization.

## Key Features:
### Checking and Removing Null Values
- df.isnull().sum()
- isnull function identify the null values in the data frame and sum function sum-up, total number of values in the data frame.

### Converting Labels SPAM and HAM into '0' and '1'
- Used LabelEncoder() to convert categorical labels (text) into numeric form.
- LabelEncoder is a class in the sklearn.preprocessing module of scikit-learn.

### Data Preprocessing
-  Utilized the nltk toolkit to preprocess text data by employing functions such as sent_tokenize and word_tokenize.
-  As a result, I enriched my DataFrame with three new columns: *number_characters, number_sentences, and number_words.*

### Model Training
-  Model is being trained using logistic regression.

### Model Efficiency
- Accuracy is used to calculate the efficiency of the model.

## Dependencies
- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- Jupyter
- NLTK
- WordCloud

## How to Run
 
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/spam-detection.git
cd spam-detection
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Run the Jupyter notebooks to see the step-by-step process of building the model:

bash
Copy code
jupyter notebook


