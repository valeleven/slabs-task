**Solution Labs Umbraco Task**


Live Link:
https://mywebapp-rifft01.azurewebsites.net
User=testinguser@test.com
Password=P@ssw0rd123



Todo Improvments and shortcomings ( due to the lack of time):

    • Making a docker image with Terraform and Azure CLI tools to avoid wasting time in downloading Azure packages
    • I’m not fimiliar with Umbraco but I’m wondering about DB migrations ??!
    • Looking into making a docker image out of the project ( very few resources available regarding Umbraco and docker support)
    • Injecting variables for Unattended Umbraco install ( not tested due to the lack of time) maybe provide entire appsettings.json as a env var?
    • Both Terraform and deployment pipeline are written as a single pipeline for ease of distribution and lack of time usually Iac could be a seperate repo and has its own pipeline that can be called from the main deployment pipeline.
    • The live links are slow due to using Azure free tier mostly :)
    
    In general the pipeline works but is a bit messy since i didn't have enough time to fine tune it to my liking... :) 
