# CODSOFT TASK1- Movie Genre Classification

This repository contains the work I completed for Task 1 of my CodSoft internship, titled "MOVIE GENRE CLASSIFICATION". The project focuses on developing a text classification system to categorize movie genres based on their descriptions.

About the Dataset
The dataset consists of movie titles, genres, and descriptions. It is divided into two parts: training and test sets. Each entry in the dataset includes:
- title: The title of the movie.
- genre: The genre of the movie (for the training set).
- description: A brief description of the movie's plot.

The training dataset contains labeled data with genres, while the test dataset contains only titles and descriptions, used for evaluating the models.

Project Highlights :

Data Cleaning and Preprocessing
- Removed noise from text data, including punctuation, stopwords, and digits.
- Applied stemming to reduce words to their root forms.

Exploratory Data Analysis (EDA)
- Visualized genre distribution in the dataset.
- Generated word clouds to showcase common words before and after cleaning.
- Analyzed the distribution of text lengths and the most common words.

 Model Training
- Transformed text data into TF-IDF features.
- Trained and evaluated three different classifiers: Naive Bayes and Logistic Regression

Model Evaluation
- Achieved promising accuracy with detailed classification reports.
- Visualized confusion matrices using a clear "coolwarm" color scheme to illustrate model performance.

Skills and Tools Used
- *Natural Language Processing:* Data cleaning, stemming, and stopwords removal.
- *Data Visualization:* Matplotlib, Seaborn for genre distribution and word clouds.
- *Machine Learning:* Naive Bayes, Logistic Regression, Support Vector Machine.
- *Python Libraries:* Pandas, NumPy, Scikit-learn, NLTK, WordCloud.


This project enhanced my skills in natural language processing, data visualization, and machine learning. I look forward to applying these skills in future tasks and continuing to learn and grow in the field of data science.

Feel free to clone the repository, explore the code, and provide any feedback. Stay tuned for more updates on my upcoming projects and tasks!
