# ![LOGO](logo.png) ServiceFabricManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ServiceFabricManagementClient API (version 2017-07-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/servicefabric-application/2017-07-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:58+03:00

## API Description

Azure Service Fabric Resource Provider API Client

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Service Fabric resource provider API operations.

> Get the list of available Service Fabric resource provider API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - The version of the Service Fabric resouce provider API

### Gets the list of application type name resources created in the specified Service Fabric cluster resource.

> Gets all application type name resources created or in the process of being created in the Service Fabric cluster resource.

*Tags:* `ApplicationType`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2017-07-01-preview" for this specification.
    Possible values: 2017-07-01-preview.

### Deletes a Service Fabric application type name resource.

> Delete a Service Fabric application type name resource with the specified name.

*Tags:* `ApplicationType`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `applicationTypeName` - _required_ - The name of the application type name resource.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2017-07-01-preview" for this specification.
    Possible values: 2017-07-01-preview.

### Gets a Service Fabric application type name resource.

> Get a Service Fabric application type name resource created or in the process of being created in the Service Fabric cluster resource.

*Tags:* `ApplicationType`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `applicationTypeName` - _required_ - The name of the application type name resource.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2017-07-01-preview" for this specification.
    Possible values: 2017-07-01-preview.

### Creates or updates a Service Fabric application type name resource.

> Create or update a Service Fabric application type name resource with the specified name.

*Tags:* `ApplicationType`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `applicationTypeName` - _required_ - The name of the application type name resource.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2017-07-01-preview" for this specification.
    Possible values: 2017-07-01-preview.

### Gets the list of application type version resources created in the specified Service Fabric application type name resource.

> Gets all application type version resources created or in the process of being created in the Service Fabric application type name resource.

*Tags:* `ApplicationTypeVersion`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `applicationTypeName` - _required_ - The name of the application type name resource.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2017-07-01-preview" for this specification.
    Possible values: 2017-07-01-preview.

### Deletes a Service Fabric application type version resource.

> Delete a Service Fabric application type version resource with the specified name.

*Tags:* `ApplicationTypeVersion`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `applicationTypeName` - _required_ - The name of the application type name resource.
* `version` - _required_ - The application type version.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2017-07-01-preview" for this specification.
    Possible values: 2017-07-01-preview.

### Gets a Service Fabric application type version resource.

> Get a Service Fabric application type version resource created or in the process of being created in the Service Fabric application type name resource.

*Tags:* `ApplicationTypeVersion`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `applicationTypeName` - _required_ - The name of the application type name resource.
* `version` - _required_ - The application type version.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2017-07-01-preview" for this specification.
    Possible values: 2017-07-01-preview.

### Creates or updates a Service Fabric application type version resource.

> Create or update a Service Fabric application type version resource with the specified name.

*Tags:* `ApplicationTypeVersion`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `applicationTypeName` - _required_ - The name of the application type name resource.
* `version` - _required_ - The application type version.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2017-07-01-preview" for this specification.
    Possible values: 2017-07-01-preview.

### Gets the list of application resources created in the specified Service Fabric cluster resource.

> Gets all application resources created or in the process of being created in the Service Fabric cluster resource.

*Tags:* `Application`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2017-07-01-preview" for this specification.
    Possible values: 2017-07-01-preview.

### Deletes a Service Fabric application resource.

> Delete a Service Fabric application resource with the specified name.

*Tags:* `Application`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `applicationName` - _required_ - The name of the application resource.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2017-07-01-preview" for this specification.
    Possible values: 2017-07-01-preview.

### Gets a Service Fabric application resource.

> Get a Service Fabric application resource created or in the process of being created in the Service Fabric cluster resource.

*Tags:* `Application`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `applicationName` - _required_ - The name of the application resource.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2017-07-01-preview" for this specification.
    Possible values: 2017-07-01-preview.

### Updates a Service Fabric application resource.

> Update a Service Fabric application resource with the specified name.

*Tags:* `Application`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `applicationName` - _required_ - The name of the application resource.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2017-07-01-preview" for this specification.
    Possible values: 2017-07-01-preview.

### Creates or updates a Service Fabric application resource.

> Create or update a Service Fabric application resource with the specified name.

*Tags:* `Application`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `applicationName` - _required_ - The name of the application resource.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2017-07-01-preview" for this specification.
    Possible values: 2017-07-01-preview.

### Gets the list of service resources created in the specified Service Fabric application resource.

> Gets all service resources created or in the process of being created in the Service Fabric application resource.

*Tags:* `Service`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `applicationName` - _required_ - The name of the application resource.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2017-07-01-preview" for this specification.
    Possible values: 2017-07-01-preview.

### Deletes a Service Fabric service resource.

> Delete a Service Fabric service resource with the specified name.

*Tags:* `Service`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `applicationName` - _required_ - The name of the application resource.
* `serviceName` - _required_ - The name of the service resource in the format of {applicationName}~{serviceName}.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2017-07-01-preview" for this specification.
    Possible values: 2017-07-01-preview.

### Gets a Service Fabric service resource.

> Get a Service Fabric service resource created or in the process of being created in the Service Fabric application resource.

*Tags:* `Service`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `applicationName` - _required_ - The name of the application resource.
* `serviceName` - _required_ - The name of the service resource in the format of {applicationName}~{serviceName}.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2017-07-01-preview" for this specification.
    Possible values: 2017-07-01-preview.

### Updates a Service Fabric service resource.

> Update a Service Fabric service resource with the specified name.

*Tags:* `Service`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `applicationName` - _required_ - The name of the application resource.
* `serviceName` - _required_ - The name of the service resource in the format of {applicationName}~{serviceName}.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2017-07-01-preview" for this specification.
    Possible values: 2017-07-01-preview.

### Creates or updates a Service Fabric service resource.

> Create or update a Service Fabric service resource with the specified name.

*Tags:* `Service`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `applicationName` - _required_ - The name of the application resource.
* `serviceName` - _required_ - The name of the service resource in the format of {applicationName}~{serviceName}.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2017-07-01-preview" for this specification.
    Possible values: 2017-07-01-preview.

## License

**flow**ground :- Telekom iPaaS / azure-com-servicefabric-application-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
