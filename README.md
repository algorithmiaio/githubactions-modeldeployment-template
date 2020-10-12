# Template ML Repository for Continous Deployment to Algorithmia via Github Actions

This is a template ML repository to get started with [Algorithmia Model Deployment Github Action](https://github.com/algorithmiaio/algorithmia-modeldeployment-action) integration, containing some necessary pieces of the integration as a starter kit. 

Algorithmia's Continuous Deployment Github Action would be a good fit for your workflow if you are using a Jupyter notebook to train and evaluate your ML model or checking your saved model file into your repository and you have your inference (algorithm) script & dependencies in your ML repo. 

After you create an algorithm on Algorithmia as the scalable inference endpoint for your ML model, you can make use of this template repository to make the configurations in your ML repository at Github. You can either take this as a starting point and use the green `Use this Template` button above to create your own repository off of this, or clone this repo and copy the desired files to over to your existing ML repository. 


## Template Repo Contents
![](images/contents.png)

## Fitting With Organizational Responsibilities
![](images/responsibilities.png)

## Example usages
Check out the two example ML repos that incorporate this Github Action to continuously deploy
  * [to an Algorithmia algorithm backed by Algorithmia](https://github.com/algorithmiaio/githubactions-modeldeployment-demo-algorithmiaalgo)
  * [to an Algorithmia algorithm backed by Github](https://github.com/algorithmiaio/githubactions-modeldeployment-demo-githubalgo)

