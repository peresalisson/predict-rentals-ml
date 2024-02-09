<h1 align="center">Bike Rentals prediction model created for dio.me using Azure AI | Machine Learning </h1>

I developed a prediction model for bike rentals for dio.me using Azure AI and Machine Learning. The process involved:

<b>Creating an Azure Machine Learning Workspace:</b> I set up all the necessary resources within Azure.

<b>Utilizing Automated Machine Learning:</b> I employed Automated ML to train the model using a dataset of historical bike rentals. The aim was to predict the number of rentals expected on a given day based on seasonal and meteorological features.

<b>Defining the Machine Learning Task as Regression:</b> The model was configured to perform regression, outputting a numerical prediction.

<b>Incorporating Data from a Web Source:</b> I used a dataset available at https://aka.ms/bike-rentals, which provided historical information on bike rentals.

<b>Deploying the Model via a Web Service:</b> This allowed for the model to be tested in a real-world scenario.

<b>Testing the Deployed Service:</b> I accessed the model through the defined endpoint (named predict-rentals) to make predictions.

<b>Reviewing the Results:</b> The model provided a predicted number of rentals based on the input data.

This description provides a structured and detailed overview of the steps involved in creating and deploying the bike rental prediction model using Azure's ML services.

You can find inside the 'endpoint.json' the Input data used to test the model.
In the 'result.json' file, you can check the result.
