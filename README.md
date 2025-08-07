# Fake_Job_Posting_Detection

📌 Project Overview
This project focuses on detecting fraudulent job postings using Natural Language Processing (NLP) and machine learning techniques. By analyzing job descriptions, company names, and other metadata, the model identifies fake job listings to help protect users from scams.
🗂️ Dataset
Dataset: Fake Job Postings Dataset
Source: [Kaggle - Fake Job Postings](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction)
The dataset includes job titles, locations, descriptions, requirements, benefits, and a label indicating whether the posting is fake.
🧠 Technologies & Tools
- Python
- Pandas & NumPy
- TF-IDF Vectorizer (for text feature extraction)
- XGBoost Classifier (for classification)
- Scikit-learn (for preprocessing and model evaluation)

⚙️ Methodology
1. Data Cleaning and Preprocessing
2. Text Feature Extraction using TF-IDF
3. Model Training using XGBoost
4. Evaluation using metrics like accuracy, precision, recall, and F1-score
5. Optional: Feature importance visualization
📈 Expected Output
- Model that classifies job postings as real or fake
- Evaluation report with classification metrics
- Visualization of top features influencing the prediction (optional)
🚀 How to Run
1. Clone the repository or download the code files.
2. Install the required libraries from `requirements.txt`.
3. Run `fake_job_detection.py` to train and test the model.
4. Use the provided sample job postings to test predictions.
📌 Future Enhancements
- Deploy the model using a web framework like Flask or Streamlit.

Confusion Matrix:
<img width="658" height="547" alt="Confusion Matrix" src="https://github.com/user-attachments/assets/a6a8d947-b899-4d70-bbfa-4e3121242fdf" />

Distribution of Fraudulent Job Postings:
<img width="558" height="393" alt="Distribution of Fraudulent Job Postings" src="https://github.com/user-attachments/assets/e5abe04c-ee07-4f8d-af62-e3dabce2f1d1" />


- Integrate real-time job data via APIs.
- Use more advanced models like BERT for better text understanding.
