![image](https://github.com/akshatabhagat6/Phishing-URL-Detection/assets/131398128/b744519e-e096-44db-a131-d22725d40635)
![image](https://github.com/akshatabhagat6/Phishing-URL-Detection/assets/131398128/d3c5ada4-ce06-45c3-98d2-8f7e93307a0d)
# Table of Content
-Introduction

-Installation

-Directory Tree

-Result

-Conclusion

# Introduction
The Internet has become an indispensable part of our life, However, It also has provided opportunities to anonymously perform malicious activities like Phishing. Phishers try to deceive their victims by social engineering or creating mockup websites to steal information such as account ID, username, password from individuals and organizations. Although many methods have been proposed to detect phishing websites, Phishers have evolved their methods to escape from these detection methods. One of the most successful methods for detecting these malicious activities is Machine Learning. This is because most Phishing attacks have some common characteristics which can be identified by machine learning methods. 
# Installation
The Code is written in Python 3.6.10. If you don't have Python installed you can find it https://www.python.org/downloads/. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning https://www.howtogeek.com/451360/how-to-clone-a-github-repository/ the repository:

pip install -r requirements.txt
# Directory Tree
├── pickle

│   ├── model.pkl

├── static

│   ├── styles.css

├── templates

│   ├── index.html

├── Phishing URL Detection.ipynb

├── Procfile

├── README.md

├── app.py

├── feature.py

├── phishing.csv

├── requirements.txt



# Technologies Used
![image](https://github.com/akshatabhagat6/Phishing-URL-Detection/assets/131398128/ee4b03b5-f7cb-49b3-86e7-a69e059cdd82)
![image](https://github.com/akshatabhagat6/Phishing-URL-Detection/assets/131398128/1da08440-4866-4155-bd03-69b83e1001f6)
![image](https://github.com/akshatabhagat6/Phishing-URL-Detection/assets/131398128/51c6deb5-9e39-4958-b265-6f4f23424c4f)
![image](https://github.com/akshatabhagat6/Phishing-URL-Detection/assets/131398128/0d0cc250-746a-4b56-8ba2-75dd484a134c)
![image](https://github.com/akshatabhagat6/Phishing-URL-Detection/assets/131398128/cd215e16-958f-4adf-94f8-abf8cecc7f1c)


# Result
Accuracy of various model used for URL detection


![image](https://github.com/akshatabhagat6/Phishing-URL-Detection/assets/131398128/84ce4229-ed5c-4a2b-aaec-1ca29677f4ec)

Feature importance for Phishing URL Detection

![image](https://github.com/akshatabhagat6/Phishing-URL-Detection/assets/131398128/bd91cdda-72a3-428a-a7ea-079953e966e4)


# Conclusion
1. The final take away form this project is to explore various machine learning models, perform Exploratory Data Analysis on phishing dataset and understanding their features.
  
2. Creating this notebook helped me to learn a lot about the features affecting the models to detect whether URL is safe or not, also I came to know how to tuned model and how they affect the model performance.
  
3. The final conclusion on the Phishing dataset is that the some feature like "HTTTPS", "AnchorURL", "WebsiteTraffic" have more importance to classify URL is phishing URL or not.
  
4. Gradient Boosting Classifier currectly classify URL upto 97.4% respective classes and hence reduces the chance of malicious attachments.
