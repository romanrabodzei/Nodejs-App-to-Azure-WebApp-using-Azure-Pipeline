# Building and Developing Node.js application to the Azure Web App using Azure Pipelines

There a simple Node.js Application for Azure Web Applicaton service. By default building infrastructure for this simple application already has been included in the azure-pipeline file. If you are going to create infrastructure using ARM template please remove the "Release Pipeline" stage from the azure-pipeline file.

## Deploy the App Service Infrastructure:

Click the button below to deploy an Azure Web App. This will create a new app service plan and web app. You can then create build and release pipelines using GitHub Actions to continuously deploy the application in this repo to the web app.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fromanrabodzei%2FNodejs-App-to-Azure-WebApp-using-Azure-Pipeline%2Fmaster%2Fazure-deploy.json" target="_blank"><img src="http://azuredeploy.net/deploybutton.png"/></a>