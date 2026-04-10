## Resource

As a user, when you purchase a service on Azure, whether it is a web hosting,
a virtual machine, or a database, your are purchasing what is referred to as
"Resource".

Its a generic object in a JSON template that represents a service you have 
purchased and remains available for the lifecycle of the service. 

Example:

```json
{
    "type": "Microsoft.Web/sites",
    "apiVersion": "2024-01-01",
    "name": "[variables('webAppPortalName')]",
    "location": "[parameters('location')]"
}
```

A resource contains all the configuration properties needed to deploy your
service.

All resources contain for common properties:
- Type
- API
- Version
- Name
- Location

Depending on the service, additional configuration options will be available.

## Resource Group

However, a resource cannot be created without a "Resource Group".

Recourse Groups are logical groupings that hold related resources for an 
application.

Resource Groups are used to group related resources sharing the same lyfecicle, 
permissions, and policies.

Consider, for example, a web app with an attached SQL database

Web App <---> Database

To jointly manage, monitor, and maintain them, simply group them in the same
Azure Resource Group.

You can use Resource Groups to control access and organize your resources after
you have deployed to Azure.

You can group your resources in different ways, including by:
- Service Type.
- Application Lifecicle.
- Department.
- Location
- etc

No one policy fits all, many organizations adopt a combination of these to
suit their specific needs. 

## ARM (Azure Resource Manager)

You can use many methods to purchase Azure services, most commonly through the
portal. 

No matter which method you choose to purchase Azure, it all goes through
the "Azure Resource Manager".

Its a centralized management layer for all Resources and Resource Groups in 
Azure, using an unified language. 

![ARM](diagrams/AzureResourceManager.drawio.png)

[Edit Diagram](diagrams/AzureResourceManager.drawio)


