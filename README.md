[![CircleCI](https://dl.circleci.com/status-badge/img/gh/BusolaAremu/Project4-UdacityCloudDevops/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/BusolaAremu/Project4-UdacityCloudDevops/tree/master)

## Project Overview.

In this project, I applied the skills acquired in this course to operationalize a Machine Learning Microservice API. 

I was given a pre-trained, `sklearn` model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. You can read more about the data, which was initially taken from Kaggle, on [the data source site](https://www.kaggle.com/c/boston-housing). 
This project tested my ability to operationalize a Python flask app—in a provided file, `app.py`—that serves out predictions (inference) about housing prices through API calls. 
This project could be extended to any pre-trained machine learning model, such as those for image recognition and data labeling.

### Project Tasks

Operationalize this working, machine learning microservice using [kubernetes](https://kubernetes.io/), which is an open-source system for automating the management of containerized applications. 
In this project I:
* Tested the project code using linting
* Completed a Dockerfile to containerize this application
* Deploy the containerized application using Docker and made a prediction
* Improved the log statements in the source code for this application
* Configured Kubernetes and created a Kubernetes cluster
* Deployed a container using Kubernetes and made a prediction
* Uploaded a complete Github repo with CircleCI to indicate that your code has been tested
