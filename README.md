# OpenAI_FlaskApp

## Prerequisites
* Azure Key Vault: To securely store the API key for OpenAI, you will need an Azure Key Vault instance and the Azure CLI. You can learn more about creating a Key Vault instance from the official documentation.

## Requirements
* Flask
* OpenAI
* BeautifulSoup
* Azure KeyVault
* Azure Identity

## How to use
* To run the local app, you can execute the following command in the terminal: ```flask --app app.py run``` 
* To use this app, you will need to send a POST request to the /gpt3 endpoint with a message in the request body (using Postman/Insomnia/etc.). The message should be formatted as a string. The response will be a JSON object that includes the following keys:

type: A string that specifies the type of message (e.g. message).
text: A string that contains the response from OpenAI. 

![image](https://user-images.githubusercontent.com/33750077/220708169-9ed1a8cc-ab5b-4cc7-b25b-6cb9036f3c20.png)
