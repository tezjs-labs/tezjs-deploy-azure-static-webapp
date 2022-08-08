# Deploy to Azure Static Web App
In this guide, you will learn how to deploy your tezjs site to Azure Static Web App.

## Deployed Url:
https://gentle-bush-08da5cf00.1.azurestaticapps.net/

## Preparing for deployment:
Run the following command to create tezjs project:
  - `npm create tez@latest`
  - `cd [projectName]`
  - `npm install` - for installing the required dependencies
  - `npm run build` - for build the project
  - `npm run dev` - for run the project

## Pre-requisites
Make sure you have:
  - Azure account.
  - node installed in your machine.
  - created a Static Web App on Azure.

## Deployment
Go to https://portal.azure.com/ to create a Static Web App on Azure  
1. Deployment from Github Repository:   
select below configurations while creating Static Web App on Azure to setup Auto Deploy

    - Source as a `Github` in Deployment details on create page
    - connect github account
    - select organization, repository and branch
    - select `Custom` build Preset
    - select App location as `/`
    - select Output location as `dist` and Api location leave it blank
   
   
## References
  - https://docs.microsoft.com/en-us/azure/static-web-apps/get-started-portal?tabs=angular&pivots=github
