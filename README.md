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
1.	Authentication: Authentication is required to ensure uninterrupted flow of operations
2.	Automated ML Experiment: Iteratively producing different ML models (various combinations of algorithms and parameters) and determining the best one
3.	Deploy the best model: Publishing the model so that it can be consumed by others
4.	Enable Application Insights and logging: Application Insights provide key performance information about the deployed service
5.	Swagger Documentation: Swagger makes documentation easier by describing the API what requests it accepts, inputs and endpoints  
6.	Consume model endpoints: Consuming the REST endpoint to interact with the trained model via POST request
7.	Create and publish a pipeline: Creating an ML pipeline and consuming the REST endpoint to interact with the pipeline via POST request
8.	Documentation: Creating a screencast showing the entire process of the working ML application and producing a README file documenting the main steps of the project. 

Step 2.1 The Registered Bankmarketing Dataset
![](Images/Step2.1-Registered%20Dataset.JPG)

Step 2.2 The Completed Experiment
![](Images/Step2.2%20-Completed%20Experiment.JPG)

Step 2.3 The Best Model
![](Images/Step2.3%20-%20Best%20Model.JPG)

Step 4.1 Running the logs.py Script
![](Images/Step4.1%20-%20logs.JPG)

Step 4.2 Enabled Applications Insights
![](Images/Step4.2%20-%20enabled%20Application%20Insights.JPG)

Step 5.1 Swagger Running on Localhost
![](Images/Step5.1%20-%20Swagger%20runs%20on%20localhost.JPG)

Step 5.2 Swagger - HTTP API Methods and Responses
![](Images/Step5.2%20-%20Swagger%20-%20HTTP%20API%20methods%20and%20responses.JPG)

Step 5.3 Swagger - HTTP API Methods and Responses (cont'd)
![](Images/Step5.3%20-%20Swagger%20-%20HTTP%20API%20Methods%20and%20responses.JPG)

Step 5.4 Swagger - HTTP API Methods and Responses (cont'd)
![](Images/Step5.4%20-%20Swagger%20-%20HTTP%20API%20methods%20and%20responces.JPG)

Step 6.1 endpoint.py Producing JSON Output
![](Images/Step6.1%20-%20endpoint.py%20producing%20JSON%20output.JPG)

Step 7.1 A Pipline is Created
![](Images/Step7.1%20-%20pipeline%20created.JPG)

Step 7.2 A Published Pipeline under the Pipeline Endpoint Tab
![](Images/step7.3%20-%20pipeline%20endpoint.JPG)

Step 7.3 The Dataset with the AutoML Module, the Published Pipeline Overview Including Active Satatus and REST Endpoint 
![](Images/Step7.4%20Dataset%20with%20AutoML%20module%20and%20the%20published%20pipeline%20overview.JPG)

Step 7.4 RunDetails Widget Showing Step Runs 
![](Images/Step7.5_RunDetail_swidget_showing_step_runs.JPG)

Step 7.5 Scheduled and Running Pipeline 
![](Images/Step7.6%20-%20Scheduled%20and%20running%20pipeline.JPG)


## Screen Recording
A link to the screencast on Youtube:
https://youtu.be/71SDksY-YX8



## Future Works
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
