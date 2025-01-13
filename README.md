# Email Spam Classifier

## Overview
This project is an **Email Spam Classifier** that uses the **Naive Bayes algorithm** to distinguish between spam and non-spam emails. The model is trained on a labeled dataset and achieves high accuracy, making it effective for real-world applications. 

The project demonstrates the end-to-end process of building a machine learning model, from data preprocessing and feature extraction to model training, evaluation, and deployment.

---

## Features
- **Spam Detection**: Classifies emails as spam or non-spam.
- **High Accuracy**: Achieves impressive performance on the test data.
- **Preprocessing Pipeline**: Includes text cleaning, tokenization, and feature extraction.
- **Streamlit Deployment**: Provides a user-friendly web interface for real-time spam detection.

---

## Technologies Used
The following technologies and libraries were used in this project:

- **Programming Language**: Python
- **Machine Learning Algorithm**: Naive Bayes (MultinomialNB from scikit-learn)
- **Libraries**:
  - **scikit-learn**: For implementing the Naive Bayes classifier and evaluating the model.
  - **NumPy**: For numerical computations.
  - **Pandas**: For data manipulation and analysis.
  - **NLTK (Natural Language Toolkit)**: For text preprocessing (e.g., tokenization, stopword removal).
  - **Matplotlib & Seaborn**: For visualizing results and data distributions.
  - **Streamlit**: For deploying the model as an interactive web application.

---

## Dataset
The dataset used in this project contains labeled emails with two categories:
- **Spam**: Emails that are irrelevant or unsolicited.
- **Non-Spam (Ham)**: Legitimate emails.
- **Dataset Download link:** https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

### Preprocessing Steps:
1. **Text Cleaning**: Removal of special characters, numbers, and punctuation.
2. **Tokenization**: Splitting text into individual words.
3. **Stopword Removal**: Removing common words that do not contribute to classification.
4. **Vectorization**: Converting text into numerical features using techniques like **TF-IDF** or **Count Vectorization**.

---

## Implementation
### 1. Install Dependencies
Ensure you have the required libraries installed:
```bash
pip install scikit-learn numpy pandas nltk matplotlib seaborn streamlit
```

### 2. Training the Model
The Naive Bayes algorithm was chosen due to its simplicity and effectiveness for text classification tasks. The model was trained using scikit-learn's `MultinomialNB` implementation.

### 3. Evaluation Metrics
The model's performance was evaluated using:
- **Accuracy**
- **Precision**

### 4. Results
The classifier achieved the following metrics:
- **Accuracy**: 95.93%
- **Precision**: 100%

---

## Deployment
The project includes a **Streamlit** application for deploying the spam classifier as a web app. Users can input email text, and the model will classify it as spam or non-spam in real time.

### Run the Streamlit App
1. Navigate to the project directory.
2. Run the following command:
```bash
streamlit run app.py
```
3. Open the provided URL in your web browser to access the application.

---

## Usage
### Clone the Repository
```bash
git clone https://github.com/yourusername/email-spam-classifier.git
cd email-spam-classifier
```

### Run the Project
1. Place your dataset in the appropriate folder.
2. Train the model and make predictions by running:
```bash
python spam_classifier.py
```
3. Deploy the Streamlit app:
```bash
streamlit run app.py
```

---

## Visualization
Key visualizations included in the project:
- **Word Cloud**: Displays the most frequent words in spam and non-spam emails.
- **Confusion Matrix**: Highlights the model's performance on the test data.

---

## Future Work
- Enhancing the Streamlit app with additional features, such as file upload for bulk email classification.
- Experimenting with advanced algorithms like Support Vector Machines (SVM) or random forest or deep learning models.

---

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

---

## Contact
For any inquiries, please contact:
**Shubham jain**  
Email: shubh.j.0705@gmail.com
GitHub: [Shubham-Jain52](https://github.com/Shubham-Jain52)

