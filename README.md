# SMS Spam Classifier

## Scenario
Spam messages are a common nuisance in today's digital communication. Identifying and filtering spam messages is crucial for maintaining a clean and efficient communication system.

## Solutions
This project provides a machine learning-based solution to classify SMS messages as spam or not spam. It uses natural language processing (NLP) techniques for text preprocessing and a trained model for prediction.

## Data Source
SMS classification dataset from Kaggle 

## Steps/Implementation
1. **Data Preprocessing**: Clean and transform the text data using tokenization, stemming, and removal of stopwords.
2. **Feature Extraction**: Convert text data into numerical features using vectorization techniques.
3. **Model Training**: Train a machine learning model using labeled data.
4. **Prediction**: Use the trained model to classify new SMS messages.

## Model Implementation
- The model is trained using a labeled dataset of SMS messages.
- It uses a vectorizer (`vectorizer.pkl`) for feature extraction and a machine learning model (`model.pkl`) for prediction.

## Final Outcome
The application predicts whether an SMS message is spam or not spam and displays the result to the user.

## Steps to Import and Run
1. Clone the repository or download the project files.
2. Install the required dependencies using:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application using:
   ```bash
   streamlit run app.py
   ```
4. Enter an SMS message in the text area and click "Predict" to see the classification result.

## Outcome
1. Normal message prediction
<img width="1002" height="462" alt="image" src="https://github.com/user-attachments/assets/dd55945f-3967-4be2-98f5-27f25cc7f0b7" />
## =========================================================================================================================================================================== ##
2. Spam message prediction
<img width="986" height="520" alt="image" src="https://github.com/user-attachments/assets/34e90c21-7eca-400c-b986-4057a137a071" />
