# Config for CI/CD Pipeline in Azure DevOps 
YAML configuration for Continuous Integration/ Continuous Deployment Pipeline in Azure DevOps Function Application. 

## About
Consists of two stages 
- Build
	- Builds package
	- Archives files
	- Publishes Archive
- Deploy 
	- Download Artifact 
 	- Deploys function app 

<img alt="Logos" src="https://i.imgur.com/syLZJO4.png"></img>

## Configurations 
You may decide to reconfigure the entire pipeline . 
However, if you wish to use this pipeline, change ``` azureSubscription``` and ``` appName``` is the ```Deploy``` stage. 


