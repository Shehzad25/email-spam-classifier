# email-spam-classifier
A machine learning-based email spam classifier using TF-IDF vectorization and Naïve Bayes. Deployed with Streamlit for real-time predictions.
📧 Email Spam Classifier
A machine learning-based email spam classifier that detects spam messages using TF-IDF vectorization and a Naïve Bayes classifier. Deployed with Streamlit for real-time predictions.

🚀 Features
Classifies emails as Spam or Not Spam
Uses TF-IDF vectorization for text processing
Implements Naïve Bayes classifier for prediction
Streamlit-based web app for easy interaction
📂 Project Structure
sql
Copy
Edit
email-spam-classifier/
│-- dataset/                # Dataset files  
│-- models/                 # Trained model files  
│-- app.py                  # Streamlit web app  
│-- train_model.py          # Script to train the model  
│-- requirements.txt        # Dependencies  
│-- README.md               # Project documentation  
🛠 Installation
Clone the repository:
bash
Copy
Edit
git clone https://github.com/Shehzad25/email-spam-classifier.git
cd email-spam-classifier
Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt
🎯 Usage
To train the model:
bash
Copy
Edit
python train_model.py
To run the web app:
bash
Copy
Edit
streamlit run app.py
📊 Model Performance
Achieved high accuracy using TF-IDF and Naïve Bayes
Evaluated with Precision
