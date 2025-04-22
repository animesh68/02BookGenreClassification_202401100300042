# 02BookGenreClassification_202401100300042
📚 Book Genre Classification

This project uses metadata such as author popularity, book length, and number of keywords to classify books into genres using a machine learning model. It also includes visual insights into the dataset and model performance.

🔧 Features

Loads and preprocesses book metadata

Trains a RandomForestClassifier to predict book genres

Visualizes:

Genre distribution

Feature importance

Confusion matrix

Generates a concise classification report

📁 Dataset

The input CSV file (book_genres.csv) must contain the following columns:

Column Name	Description

author_popularity	Numerical score indicating author fame

book_length	Length of the book (pages or words)

num_keywords	Number of descriptive keywords

genre	Target genre label

📊 Output

Classification Report: Precision, recall, F1-score

Genre Distribution: Count of each genre in dataset

Feature Importance: How much each feature influences the model

Confusion Matrix: Comparison of actual vs predicted genres

👨‍💻 Author

Developed by [Animesh] – happy to collaborate and enhance this further!
