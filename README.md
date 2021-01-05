# Operationalising Machine Learning

## Overview
The project consists of two parts. The aim of the first part is to configure, deploy and consume a cloud-based ML production model using Azure. The aim of the second part is to create, publish and consume a pipeline. The Bank Marketing dataset is used to train the models in the first and the second parts.


## Architectural Diagram

![](Images/Diagram.JPG)

Part 1
1. Registering the dataset to make it available in the Azure workspace for the Automated ML Experiment
2. Using Automated ML to determine the best model
3. Deploying the best model so that it can be consumed
4. Consuming the REST endpoint to interact with the trained model via POST request

Part 2
1. Using the same dataset registered in Azure workspace for part 1.
2. Creating a ML pipeline and AutoML Step - workflow automation
3. Publishing the pipeline so that it can be consumed
4. Consuming the REST endpoint to interact with the pipeline via POST request


## Key Steps

### Project main steps
1.	Authentication
2.	Automated ML Experiment
3.	Deploy the best model
4.	Enable logging
5.	Swagger Documentation
6.	Consume model endpoints
7.	Create and publish a pipeline
8.	Documentation


## Screen Recording
A link to the screencast on Youtube:
https://youtu.be/71SDksY-YX8



## Future Works
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
