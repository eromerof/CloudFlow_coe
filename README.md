# CloudFlow_coe

CloudFlow_coe is a complement for Microsoft Power Platform CoE starter kit that be able to register all cloud flow execution within dataverse coe's environment. 

## How to install

Install the managed solution included in the release's section in your coe environment. In the solution there is a unique reference conection with an http with azure ad connector
**it's necessary that you must configure the connection http with azure ad with these parameters:**

Base Resource URL: https://emea.api.flow.microsoft.com/

Azure AD Resource URI (Application ID URI): https://service.flow.microsoft.com/

**it's necessary that you configure the production environment id variable**

You must go to https://make.powerapps.com, select the environment that you want to receive notifications and you can find the environment id information in developer resources: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/view-download-developer-resources 



