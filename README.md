![68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f382f38342f4d6174706c6f746c69625f69636f6e2e737667](https://github.com/akshatabhagat6/Phishing-URL-Detection/assets/131398128/01745ae1-adbd-4f76-9e15-e9243615b859)![68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f652f65642f50616e6461735f6c6f676f2e737667](https://github.com/akshatabhagat6/Phishing-URL-Detection/assets/131398128/83dffff7-d947-4df8-9d58-02bf67a361c8)![68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f332f33312f4e756d50795f6c6f676f5f323032302e737667](https://github.com/akshatabhagat6/Phishing-URL-Detection/assets/131398128/17f7ed4e-f61b-4504-98b0-8fb8e9dcd33d)# Phishing-URL-Detection 
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

https://numpy.org/doc/
![image](https://github.com/akshatabhagat6/Phishing-URL-Detection/assets/131398128/7f677b1e-095d-4a71-8651-8874b26fab41)
https://camo.githubusercontent.com/e697b78d800b99e49d5220298ca5b72e74d31a7285bc0cc2615a9a104ab7e766/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f382f38342f4d6174706c6f746c69625f69636f6e2e737667
https://camo.githubusercontent.com/1d558c40dabf9c6ba6000aee6bf0831cbae21ee825097a26049f98757ba071fb/68747470733a2f2f7363696b69742d6c6561726e2e6f72672f737461626c652f5f7374617469632f7363696b69742d6c6561726e2d6c6f676f2d736d616c6c2e706e67
https://camo.githubusercontent.com/f1611193d342b3da4eded1577f0d0aba7cc97f4f229c0edce7b35c986707ecfe/68747470733a2f2f656e637279707465642d74626e302e677374617469632e636f6d2f696d616765733f713d74626e3a414e643947635363712d786f634c63744c30374a79307470525f703977305134325f724b3161416b4e665736736d3375636a464b574d4c333961614a50676468616479436e45694b37767726757371703d434155
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
