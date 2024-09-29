# Overview
An overview of the project
In this project, We will build a Github repository from scatch and create a scaffolding in performing
both Continuous Integration and Continuous Delevery.
 1. Using Github Actions along with a Makefile, requirements.txt and application code to perform an initial lint, test, and install cycle.
 2. Integrating this project with Azure Pipelines to enable Continuous Delivery to Azure App Service.
 3. Using Azure Cloud shell in this project
Architectural Diagram
![Screen Shot 2024-09-29 at 16 48 16](https://github.com/user-attachments/assets/3edc738e-d80f-46f0-897f-ad68bfddc5af)

Instructions for running the Python project
A short description of how to improve the project in the future
## Enhancement
1. Build effective microservices
2. Build effective alerts that are useful and actionable

Screen demonstrating key steps

## Project Plan
* A link to a Trello board for the project : 
Link: https://trello.com/b/1zEYv7Jb/agile-sprint-board-for-project-2

* A link to a spreadsheet that includes the original and final project plan>
* 
The original plan: https://docs.google.com/spreadsheets/d/1eR3HQicnxS8ViLmIkH72xg544pAvudNPIUVrg8txbb4/edit?usp=sharing

The final plan: https://docs.google.com/spreadsheets/d/1aGdouEsXQkD_rF0C4O6q5vfOcGaLmR0eJHsEQoU4osI/edit?usp=sharing

## Instructions

<TODO:  
* Architectural Diagram (Shows how key parts of the system work)>

<TODO:  Instructions for running the Python project.  How could a user with no context run this project without asking you for any help.  Include screenshots with explicit steps to create that work. Be sure to at least include the following screenshots:

* Project running on Azure App Service

* Project cloned into Azure Cloud Shell

* Passing tests that are displayed after running the `make all` command from the `Makefile`

* Output of a test run

* Successful deploy of the project in Azure Pipelines.
 ![Screen Shot 2024-09-29 at 16 56 51](https://github.com/user-attachments/assets/ed0089f8-0775-45c6-a55a-63afe30d8b59)


* Running Azure App Service from Azure Pipelines automatic deployment

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction]([(https://github.com/TuanNA163/flask-learn-udacity/blob/main/make_predict_azure_app.sh)]).
The output should look similar to this:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[2.431574790057212]}
```

* Output of streamed log files from deployed application


## Demo 

<TODO: Add link Screencast on YouTube>
