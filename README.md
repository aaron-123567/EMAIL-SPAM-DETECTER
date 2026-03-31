📧 Spam Email Checker

This is a simple machine learning project that can tell whether an email is spam or not spam.

I built this project to better understand how text classification works and how machine learning models can be used in real-world situations. Instead of making it overly complex, I focused on keeping things simple and clear — from taking input text to making predictions.

🚀 What This Project Does
Takes email text as input
Cleans and preprocesses the text
Converts the text into numbers using TF-IDF
Uses a trained model to classify the email
Shows whether the email is spam or not
📁 Project Structure
Spam_Email_Classifier/
│
├── data/
│   └── spam.csv
│
├── models/
│   ├── model.pkl
│   └── vectorizer.pkl
│
├── preprocess.py
├── train.py
├── email_checker.py
└── requirements.txt
⚙️ How to Run

First, go to the project folder:

cd Spam_Email_Classifier

Then install the required libraries:

pip install -r requirements.txt

Train the model:

python train.py

Finally, run the email checker:

python email_checker.py
🧑‍💻 How to Use
Type or paste an email into the terminal
Press Enter
The model will tell you if it's spam or not
You can continue checking more emails if you want
💡 Example Inputs

Spam:

Congratulations! You have won a free prize

Not Spam:

Hi, are we meeting tomorrow for the project?
📚 What I Learned

While working on this project, I got hands-on experience with:

Text preprocessing
TF-IDF vectorization
Naive Bayes classification
Saving and loading models
Building a simple command-line tool
📝 Notes
This is a beginner-friendly project made for learning purposes
The accuracy depends on the dataset used
It can definitely be improved by using more data or better models
👤 Author

Aaron Steve R

This project is part of my journey in learning machine learning and understanding how models work with text data in real-world applications.