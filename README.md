# Recommendation-System-For-Research-Papers
This system allows junior and senior researchers to probe through series of research papers and get access to relevant papers that suit their description and topic.

# Project Structure 
There are four main sections to this project:

Model.py includes the code for our machine learning model that uses training data from the 'papers.csv' file to suggest research publications.

App.py provides Flask APIs that compute the predicted value using our model and return it after receiving research paper details through a GUI or API request.

Request.py - This calls APIs that have previously been created in app.py using the requests module and displays the result.

templates - This folder has the HTML template that users may use to enter their search query information and see the suggested research articles.

