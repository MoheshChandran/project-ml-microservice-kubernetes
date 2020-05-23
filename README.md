[![CircleCI](https://circleci.com/gh/MoheshChandran/project-ml-microservice-kubernetes.svg?style=svg)](https://circleci.com/gh/MoheshChandran/project-ml-microservice-kubernetes)

## Project Summary

In this project, i have apply the skills that i have acquired in this course to operationalize a Machine Learning Microservice API. 

Given a pre-trained, `sklearn` model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. Based on the given model, i have to deploy this model into production system. The application need to be containerized using docker and also kubernetes.

So by end of the project, we will get a complete scalable machine learning service that's available via Flask API.

## Setup the Environment

* Create a virtualenv and activate it
* Run `make install` to install the necessary dependencies
* Run make lint to makesure the code works

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
