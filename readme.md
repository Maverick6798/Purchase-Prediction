# Pridiction Of Purchase

This is a Purchase Prediction **Machine Learning model** created with the help of *Logistic Regression* to determine the puchase of Car on the basis of age and estimated salary.

### It detects images using deep learning and python

I will be using **Logistic Regression** in this project,in perticular it is trained on dataset provided of Kaggle.
 
## Installation

	* pip3 install numpy
	* pip3 install flask 
	* Docker

## Working Process

The model is built on python program and later on it is connected to the **flask** which helps it to deploy on webserver.
Webpages are built on HTML and CSS.
Docker and Dockerfile is used to convert all of it into an OS(image).
That image is later on pushed on **Docker Hub** for public use.
To pull that image from Docker Hub
		**docker pull maverick6798/logistic**
All the files later on are uploaded on github.

## To Run The Project

   1. Download the docker 
   2. Use these command on terminal -
   			***docker pull maverick6798/logistic***
  		    ***docker run -dit maverick6798/logistic***
   3. Go to your browser and use URL ***0.0.0.0:5000***.
   4. Enter the age and estimated salary of that person. 

#### NOTE
*There is a chance that docker might not open image. so use command* ***setenforce 0*** *before running the image.*