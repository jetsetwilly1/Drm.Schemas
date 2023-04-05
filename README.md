# Dynamics Resource Management (DRM) Templates

Powershell Module: https://www.powershellgallery.com/packages/Drm.Templates.Powershell

## Drm.Schemas

These schemas can be located at https://schemas.drmtemplates.io/2021-03-01/deploymentTemplate.json#

They are used for validating and compiling DRM Templates as part of the Powershell module here
https://github.com/jetsetwilly1/Drm.Powershell.


## About DRM Templates

Dynamics Resource Management Templates (DRM) was built with Devops Engineers and Dynamics developers in mind. Based on 
ARM Templates, they are constructed in the same way and offer many of the same functionality.

Managing multiple Dynamics environments can be challenging but by using this tool, 
environments can be easily maintained and controlled all through your automation pipelines.

DRM Templates allow you to 'PATCH' entities with your configuration. This includes custom entities. 
A common scenario for a Dynamics environment is to build Queues and Teams for example. 
Not only can you manage basic properties of these entities but you can also apply members to your queues and teams.

All entities are documented by Microsoft [here](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/reference/entitytypes?view=dataverse-latest) enabling you to get to grips with any 
entity you might need to configure.

For more information on DRM Templates take a look at the documentation here https://docs.drmtemplates.io/tutorials/quickstart.html