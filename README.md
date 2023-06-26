
# Flight Fare Prediction
## Demo

Link: http://ec2-16-170-211-147.eu-north-1.compute.amazonaws.com/

## Overview
This is a Flask web app which predicts fare of Flight ticket.

## Installation

The Code is written in Python 3.10. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:



```bash
  pip install -r requirements.txt
```

## Deployement on AWS Ec2





Login or signup in order to deploy app on AWS Ec2 . Than create a instence on Ec2 and configure server and securities than download ssh key. Make a connection between Winscp and upload project on server than go to server console by connect to instence here mine server was ubuntu. Now install necessary requirments and also install nginx web server and also gunicorn then run flask app

![App Screenshot](https://appinventiv.com/wp-content/uploads/sites/1/2022/07/Login-into-your-AWS-Account-and-open-EC2-Dashboard-scaled.webp)

![App Screenshot](https://cdn-media-1.freecodecamp.org/images/RooSvbKlAWsOjkz8JPactXH-GPf4Pe6DC3Ue)

![App Screenshot](https://miro.medium.com/v2/resize:fit:1200/1*AwVgJVFKngWFFTPuHDyNyA.jpeg)

## Directory Tree
```bash

├── templates
│   ├── app.html
├── README.md
├── app.py
├── Flight Fare Prediction.ipynb
├── fare_predict.pkl
├── requirements.txt
```

## Technologies Used
![App Screenshot](https://www.datasciencecentral.com/wp-content/uploads/2021/10/1157930838.jpg)

![App Screenshot](https://miro.medium.com/v2/resize:fit:1400/1*Zrw9rx_RY8wO3Tlax9LE1w.png)

## Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an [issue](https://github.com/gopsa2001/Flight-fare-prediction/issues) here by including your search query and the expected result

## Thank you