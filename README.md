# mlops-design-test

Project instructions
Design an initial draft of the MLOps considerations for a company that has ~20 to 50 Machine Learning models running inference in real time for upwards of 100.000 users monthly. Include as much detail as you want, drawing, diagrams, or whatever else you feel may give us an idea on your expertise with MLOps in general. Feel free to name specific technologies and libraries that you would use to solve the problem.



Some assumptions you can take:

All infrastructure is on AWS.
Assume you have unlimited budget and can use any AWS service.
Assume each model runs on an standalone Kubernetes pod or EC2 instance for inference. Each of them is accessed through a REST API built on FastAPI.
All the Data Engineering has been done to get clean data for any given model to a Redshift DataWarehouse.


Some of the things we would like for you to cover:

Inference Scalability.
Machine Learning CI/CD. 
Model Validation (Data Drift and Model Drift).
Data Versioning.
Model Continuous Training.
Anything else that you may consider important as a MLOps practitioner.


Feel free to Google and research about anything you feel necessary. If you want to let us know you are particularly good at one particular subject, let us know. If you don't know enough about one particular subject, let us know. We don't expect you to be an expert in everything that was presented.



Code is not necessary but allowed if you want to code something up.



How to submit
Upload your completed project to your GitHub including all images, text, code, or anything else you may want to share, and then paste a link to the repository below in the form along with any comments you have about your solution.
