#Phishing Website Detection using ML and Flask

Phishing is a prevalent form of cyber-attack where users are tricked into visiting illegitimate websites. These websites can lead to the exposure of sensitive information such as usernames, passwords, bank details, and card details. In this project, we focus on detecting phishing websites using machine learning techniques by analyzing features extracted from their URLs.

Project Overview
Objective: Detect phishing websites based on URL features.
Approach: Utilize machine learning classification (specifically, the Random Forest algorithm) to analyze URL metadata.
Dataset: The dataset contains labeled phishing and non-phishing URLs.
Feature Extraction: Extracted features include the number of dots, presence of hyphens, URL length, presence of “@” symbol, number of subdirectories, number of subdomains, domain length, number of queries, presence of IP addresses, and suspicious top-level domains (TLDs).
Model Accuracy: The Random Forest algorithm provides robust results without overfitting the data.
Repository Contents
README.md: Overview and instructions for the project.
app.ipynb: Jupyter Notebook with code for feature extraction and model training.
app.py: Flask API for deploying the trained model.
data.csv: Dataset containing labeled URLs.
dataset.png: Visual representation of the dataset.
detection.py: Code for detecting phishing websites.
features.png: Visual representation of extracted features.
front_end.png: Front-end design using Flask and HTML.
models.png: Diagram illustrating the model architecture.
url_train_dataset.csv: Dataset used for training the model.
Installation and Usage
Clone the Repository:
git clone https://github.com/rsrogan/tool-to-detect-phishing-website.git

Install Dependencies:
pip install -r requirements.txt

Run the Flask App:
python app.py

Access the Web Interface: Open your web browser and navigate to http://localhost:5000.
Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.
