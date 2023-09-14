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
│   ├── model.pkl
├── static
│   ├── styles.css
├── templates
│   ├── index.html
├── Phishing URL Detection.ipynb
├── Procfile
├── README.md
├── app.py
├── feature.py
├── phishing.csv
├── requirements.txt


# Technologies Used

![Upload<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 721.86 324.74"><defs><style>.cls-1{fill:#4d77cf;}.cls-2{fill:#4dabcf;}</style></defs><g id="Layer_1" data-name="Layer 1"><path class="cls-1" d="M299.23,125a5.76,5.76,0,0,1,1.62.45,5.58,5.58,0,0,1,1.38.93,17,17,0,0,1,1.49,1.62l41.51,52.47c-.17-1.67-.28-3.31-.36-4.88s-.12-3.07-.12-4.47V124.83h17.87v87.38H352.06a9.68,9.68,0,0,1-3.95-.72,8.47,8.47,0,0,1-3.12-2.64l-41.21-52c.13,1.51.22,3,.3,4.46s.13,2.83.13,4.11v46.84H286.33V124.83H297A17.21,17.21,0,0,1,299.23,125Z"/><path class="cls-1" d="M392,150v39.46q0,4.62,2.1,7.14a7.62,7.62,0,0,0,6.18,2.52,13.26,13.26,0,0,0,5.73-1.26,21.37,21.37,0,0,0,5.19-3.54V150h18.59v62.19H418.28a4.39,4.39,0,0,1-4.57-3.12l-1.13-3.6a37.32,37.32,0,0,1-3.72,3.16,23.32,23.32,0,0,1-4.11,2.39A24.55,24.55,0,0,1,400,212.6a25,25,0,0,1-5.51.57,21.75,21.75,0,0,1-9-1.77,18.67,18.67,0,0,1-6.63-4.94,21.68,21.68,0,0,1-4.08-7.5,31,31,0,0,1-1.38-9.48V150Z"/><path class="cls-1" d="M441.78,212.21V150H453.3a5.13,5.13,0,0,1,2.91.78,4.21,4.21,0,0,1,1.65,2.34l1,3.36a33.22,33.22,0,0,1,3.23-3,20.83,20.83,0,0,1,3.63-2.34,19.68,19.68,0,0,1,9.15-2.13,14.6,14.6,0,0,1,9.33,2.91,18.14,18.14,0,0,1,5.6,7.76,18.71,18.71,0,0,1,3.81-4.92,20.42,20.42,0,0,1,4.86-3.29,23.69,23.69,0,0,1,5.51-1.86,28.63,28.63,0,0,1,5.8-.6,26.3,26.3,0,0,1,9.47,1.59,18.05,18.05,0,0,1,6.93,4.62,20.15,20.15,0,0,1,4.23,7.44,32,32,0,0,1,1.44,10v39.52h-18.6V172.69q0-9.66-8.27-9.65a8.46,8.46,0,0,0-6.27,2.49q-2.49,2.47-2.49,7.16v39.52H477.65V172.69q0-5.34-2.1-7.5c-1.4-1.44-3.46-2.15-6.18-2.15a10.53,10.53,0,0,0-4.77,1.13,17.72,17.72,0,0,0-4.23,3.06v45Z"/><path class="cls-1" d="M562.93,183v29.21H542.66V124.83h30.82A50.86,50.86,0,0,1,589.35,127a30.49,30.49,0,0,1,10.91,6,23.36,23.36,0,0,1,6.33,9.06,30.63,30.63,0,0,1,2,11.27,33.11,33.11,0,0,1-2.1,12,24.08,24.08,0,0,1-6.42,9.36,30,30,0,0,1-10.94,6.08A49.9,49.9,0,0,1,573.48,183Zm0-15.29h10.55c5.28,0,9.08-1.25,11.4-3.78s3.48-6,3.48-10.55a15.79,15.79,0,0,0-.9-5.46,11.11,11.11,0,0,0-2.73-4.23,12.41,12.41,0,0,0-4.62-2.73,20.71,20.71,0,0,0-6.63-1H562.93Z"/><path class="cls-1" d="M644.61,228.35a6.69,6.69,0,0,1-2,2.72,6.62,6.62,0,0,1-3.84.87H624.82l12-25.18L612,150h16.43a5.25,5.25,0,0,1,3.36,1,5.15,5.15,0,0,1,1.68,2.28l10.19,26.81A59,59,0,0,1,646,187.5c.4-1.28.84-2.54,1.32-3.77s.94-2.5,1.38-3.78l9.24-26.69a4.5,4.5,0,0,1,1.89-2.31,5.4,5.4,0,0,1,3-.93h15Z"/><polygon class="cls-2" points="132.38 96.4 95.25 77.66 54.49 98 92.63 117.15 132.38 96.4"/><polygon class="cls-2" points="149.41 104.99 188.34 124.65 147.95 144.93 109.75 125.75 149.41 104.99"/><polygon class="cls-2" points="201.41 77.94 241.41 98 205.63 115.96 166.62 96.28 201.41 77.94"/><polygon class="cls-2" points="184.19 69.3 148.18 51.24 112.56 69.02 149.67 87.73 184.19 69.3"/><polygon class="cls-2" points="156.04 224.36 156.04 273.5 199.66 251.73 199.62 202.57 156.04 224.36"/><polygon class="cls-2" points="199.6 185.41 199.55 136.77 156.04 158.4 156.04 207.06 199.6 185.41"/><polygon class="cls-2" points="251.97 176.3 251.97 225.63 214.76 244.19 214.73 195.09 251.97 176.3"/><polygon class="cls-2" points="251.97 159.05 251.97 110.71 214.69 129.24 214.72 177.98 251.97 159.05"/><path class="cls-1" d="M140.64,158.4l-29.38-14.78v63.84S75.32,131,72,124.13c-.43-.89-2.19-1.86-2.64-2.1C62.88,118.65,44,109.09,44,109.09V221.92l26.12,14v-59s35.55,68.32,35.92,69.07,3.92,7.94,7.74,10.47c5.07,3.37,26.84,16.46,26.84,16.46Z"/></g></svg>ing 68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f332f33312f4e756d50795f6c6f676f5f323032302e737667.svg…]()

    ![Uploading 68747470<svg id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 818.63 331.21"><defs><style>.cls-1{fill:#130754;}.cls-2{fill:#ffca00;}.cls-3{fill:#e70488;}</style></defs><title>Artboard 63</title><path class="cls-1" d="M290.85,199.21c-10.27,0-20.73-4.25-27.28-12.58v45H243l0-111.09h18.6l.71,12.22c6.38-9.39,17.71-14.35,28.52-14.35,20.73,0,36,17.37,36,40.4S311.58,199.22,290.85,199.21Zm-6.37-65.55c-12.05,0-21.79,9.39-21.79,25.16S272.43,184,284.48,184s21.79-9.39,21.79-25.16S296.53,133.66,284.48,133.66Z"/><path class="cls-1" d="M404.36,197.1l-.71-12.22c-6.38,9.39-17.72,14.35-28.53,14.34-20.73,0-36-17.36-36-40.39s15.24-40.4,36-40.39c10.81,0,22.15,5,28.53,14.35l.71-12.22H423V197.1Zm-22.85-63.43c-12.05,0-21.79,9.39-21.8,25.16S369.45,184,381.5,184s21.8-9.39,21.8-25.16S393.56,133.67,381.51,133.67Z"/><path class="cls-1" d="M494.87,197.11V154.77c0-14.88-5.13-19.84-14.52-19.84-9.75,0-20.38,8.85-20.38,19.48v42.7H439.41V120.57H458.2l.89,14.18c5.14-9.75,16.65-16.3,28.35-16.3,20.37,0,28,14.18,28,33.13v45.54Z"/><path class="cls-1" d="M590.77,197.13l-.71-12.23c-6.38,9.39-17.72,14.35-28.52,14.35-20.73,0-36-17.37-36-40.4s15.24-40.39,36-40.39c10.27,0,20.72,4.26,27.28,12.58V90.83h20.56l0,106.3ZM567.92,133.7c-12,0-21.79,9.39-21.79,25.15S555.87,184,567.92,184s21.79-9.38,21.79-25.15S580,133.7,567.92,133.7Z"/><path class="cls-1" d="M686.6,197.14l-.71-12.22c-6.38,9.39-17.72,14.34-28.53,14.34-20.73,0-36-17.36-36-40.4s15.24-40.39,36-40.39c10.81,0,22.15,5,28.53,14.36l.71-12.23h18.6v76.53Zm-22.85-63.43c-12,0-21.79,9.39-21.8,25.16S651.7,184,663.74,184s21.8-9.39,21.8-25.16S675.8,133.71,663.75,133.71Z"/><path class="cls-1" d="M750.73,199.63a60.16,60.16,0,0,1-30.65-8.69l3.37-14.17c6.2,3.72,15.59,8.51,26.93,8.51,8.15,0,13.82-2.48,13.82-8.86,0-5.49-5.85-7.44-16.3-9.92-18.78-4.08-25.51-14-25.51-24.81,0-12.05,9.39-23.38,30.12-23.38,12.58,0,23.57,5.49,26,6.91l-3.37,13.47A44.59,44.59,0,0,0,753,132.31c-8.32,0-12.4,2.83-12.4,7.44,0,5.13,5.32,7.44,13.46,9.39,20.2,4.25,28.35,13.64,28.35,23.92C782.45,189.53,770.4,199.63,750.73,199.63Z"/><rect class="cls-1" x="74.88" y="68.42" width="24.09" height="50.02"/><rect class="cls-1" x="74.88" y="171.17" width="24.09" height="50.02"/><rect class="cls-2" x="74.88" y="133.04" width="24.09" height="23.6"/><rect class="cls-1" x="36.19" y="109.55" width="24.09" height="166.27"/><rect class="cls-1" x="112.78" y="212.44" width="24.09" height="50.02"/><rect class="cls-1" x="112.78" y="109.61" width="24.09" height="50.02"/><rect class="cls-3" x="112.78" y="174.23" width="24.09" height="23.6"/><rect class="cls-1" x="150.67" y="55.39" width="24.09" height="166.27"/></svg>733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f652f65642f50616e6461735f6c6f676f2e737667.svg…]()

![Uploading<?xml version="1.0" encoding="UTF-8"?>
<svg xmlns="http://www.w3.org/2000/svg" width="180" height="180" stroke="gray">
<g stroke-width="2" fill="#FFF">
<circle cx="90" cy="90" r="88"/>
<circle cx="90" cy="90" r="66"/>
<circle cx="90" cy="90" r="44"/>
<circle cx="90" cy="90" r="22"/>
<path d="m90,2v176m62-26-124-124m124,0-124,124m150-62H2"/>
</g><g opacity=".8">
<path fill="#44C" d="m90,90h18a18,18 0 0,0 0-5z"/>
<path fill="#BC3" d="m90,90 34-43a55,55 0 0,0-15-8z"/>
<path fill="#D93" d="m90,90-16-72a74,74 0 0,0-31,15z"/>
<path fill="#DB3" d="m90,90-58-28a65,65 0 0,0-5,39z"/>
<path fill="#3BB" d="m90,90-33,16a37,37 0 0,0 2,5z"/>
<path fill="#3C9" d="m90,90-10,45a46,46 0 0,0 18,0z"/>
<path fill="#D73" d="m90,90 46,58a74,74 0 0,0 12-12z"/>
</g></svg> 68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f382f38342f4d6174706c6f746c69625f69636f6e2e737667.svg…]()
![68747470733a2f2f7363696b69742d6c6561726e2e6f72672f737461626c652f5f7374617469632f7363696b69742d6c6561726e2d6c6f676f2d736d616c6c2e706e67](https://github.com/akshatabhagat6/Phishing-URL-Detection/assets/131398128/88d927d9-b8d7-4abc-83fc-905b43abe2a0)

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
