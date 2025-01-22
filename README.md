# CI-Project
Integrated with Sonarqube, Nexus, Slack

The vProfile Project is a Java-based web application that follows a CI/CD pipeline using Jenkins, Maven, SonarQube, Nexus, and Slack notifications. This documentation outlines the pipeline setup, integration with tools, and the workflow used to automate build, test, code quality analysis, and artifact deployment.
CI/CD Pipeline Workflow
The pipeline consists of the following stages:
1.	Fetch Code: Clones the repository from GitHub.
2.	Build: Compiles the application using Maven.
3.	Unit Testing: Runs automated tests.
4.	Code Analysis (Checkstyle & SonarQube): Ensures code quality and security.
5.	Quality Gate Check: Validates code against SonarQube quality gate.
6.	Upload Artifacts to Nexus: Stores built artifacts in Nexus Repository.
7.	Slack Notification: Sends build status notifications to Slack.


<img width="960" alt="jenkins2" src="https://github.com/user-attachments/assets/3c8765b4-eb66-4833-991d-6d2c55f9e945" />
