# Bank Note Authentication

## 📌 Introduction

This Machine Learning Web Application uses a several features of Banknotes to predict the Authenticy of Banknotes weither it is Genuine or Forged with an accuracy of 99.81% using KNeighborsClassifier. This Dataset is taken from UCI Repository and also available in Kaggle,Data were extracted from images that were taken from genuine and forged banknote-like specimens. For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tool were used to extract features from images,***In this ml model we are considering 0 for forged bank note and 1 for geniune bank note.***

Attribute Information:
1. variance of Wavelet Transformed image (continuous)
2. skewness of Wavelet Transformed image (continuous)
3. curtosis of Wavelet Transformed image (continuous)
4. entropy of image (continuous)
5. class (integer)

## 🎯 Purpose of the Project

Whether we pull out paper bills or swipe a credit card, most of the transactions we engage in daily use currency. Indeed, money is the lifeblood of economies around the world. Currency refers to paper money or coins that are in circulation. But currency is actually only a small piece of the monetary economy and just one consideration when looking at the total money supply.

Indeed, most money today exists as credit money or as electronic records stored in databases in banks or financial institutions. But still, the bread and butter of everyday transactions is currency, and that is what we will look more closely at here.

### Why Bank Notes Genuinity is Important 💵?
As now a days many transactions take place using plastic money , But Bank Notes and Coins are still is in the use and used by more than 56% of Indians as surveyed in 2019 and the major transactions from buying daily households to spending money in various places to buy things in small commodities shop to Barber Shops and Groceries are taken place in notes and if the notes used by people of the country are forged or duplicate this will leads to unstable economy and rise of crimes in country with illegal transactions, so we need to autheticate notes so that it can leads to stable economy and leads towards a well development of country.

## Installation
The Code is written in Python 3.7.3 If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download Heroku CLI to manually deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Directory Tree 
```

├── templates
│   ├── index.html
├── Procfile
├── README.md
├── app.py
├── Car Price Prediction model.ipynb
├── random_forest_regression_model.pkl
├── requirements.txt
```


## Frontend Using Streamlit
https://banknotesauthentication.herokuapp.com/

![image](https://user-images.githubusercontent.com/75041273/119726176-74414480-be8e-11eb-9643-784b82e6742c.png)


## 🏁 Technology Stack

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

* [SkLearn](https://scikit-learn.org/)
* [Streamlit](https://www.streamlit.io/)
* [Heroku](https://www.heroku.com/)



## 📋 Further Changes to be Done

- [ ] Deploying the Web Application on Cloud.
     - [ ] Google Cloud 
     - [ ] Azure
     - [ ] AWS EC2 Instance




