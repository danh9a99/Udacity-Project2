# Disaster Response Pipeline Project

- This course taught me and helped me improve my data engineering skills, which will expand my opportunities and potential as a data scientist. I'll use these skills in this project to analyze disaster data from Appen and build a model for an API that classifies disaster notifications.
- An individual may enter a fresh message into a web application and receive classification results for the message in many categories. Data visualizations are also shown via the online application.

## Project Structure:


README.md
- app
 	+ run.py # Flask file that runs app
 	+ templates
 	+ go.html # Classification result page of web app
 	+ master.html # Main page of web app
- data
 	+ Project2-Udacity.db # Database to save clean data
 	+ disaster_categories.csv # Input data to process
 	+ disaster_messages.csv # Input data to process
 	+ process_data.py # ETL pipeline
- models
 	+ train_classifier.py # ML pipeline

## Instruction:

- Run the following commands in the project's root directory to set up your database and model.

	+ To run ETL pipeline that cleans data and stores in database python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db
	+ To run ML pipeline that trains classifier and saves python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl
- Go to app directory: cd app

- Run your web app: python run.py

- Go to http://0.0.0.0:3000/
