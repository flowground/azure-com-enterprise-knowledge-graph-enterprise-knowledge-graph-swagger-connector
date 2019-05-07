# ![LOGO](logo.png) Azure Enterprise Knowledge Graph Service **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure Enterprise Knowledge Graph Service API (version 2018-12-03).

Generated from: https://api.apis.guru/v2/specs/azure.com/EnterpriseKnowledgeGraph-EnterpriseKnowledgeGraphSwagger/2018-12-03/swagger.json<br/>
Generated at: 2019-05-07T17:38:08+03:00

## API Description

Azure Enterprise Knowledge Graph Service is a platform for creating knowledge graphs at scale.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all the available EnterpriseKnowledgeGraph services operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request.

### Returns all the resources of a particular type belonging to a subscription.

*Tags:* `EnterpriseKnowledgeGraph`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Returns all the resources of a particular type belonging to a resource group

*Tags:* `EnterpriseKnowledgeGraph`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the EnterpriseKnowledgeGraph resource group in the user subscription.
* `subscriptionId` - _required_ - Azure Subscription ID.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Deletes a EnterpriseKnowledgeGraph Service from the resource group.

*Tags:* `EnterpriseKnowledgeGraph`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the EnterpriseKnowledgeGraph resource group in the user subscription.
* `resourceName` - _required_ - The name of the EnterpriseKnowledgeGraph resource.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Returns a EnterpriseKnowledgeGraph service specified by the parameters.

*Tags:* `EnterpriseKnowledgeGraph`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the EnterpriseKnowledgeGraph resource group in the user subscription.
* `resourceName` - _required_ - The name of the EnterpriseKnowledgeGraph resource.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Updates a EnterpriseKnowledgeGraph Service

*Tags:* `EnterpriseKnowledgeGraph`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the EnterpriseKnowledgeGraph resource group in the user subscription.
* `resourceName` - _required_ - The name of the EnterpriseKnowledgeGraph resource.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Creates a EnterpriseKnowledgeGraph Service. EnterpriseKnowledgeGraph Service is a resource group wide resource type.

*Tags:* `EnterpriseKnowledgeGraph`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the EnterpriseKnowledgeGraph resource group in the user subscription.
* `resourceName` - _required_ - The name of the EnterpriseKnowledgeGraph resource.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

## License

**flow**ground :- Telekom iPaaS / azure-com-enterprise-knowledge-graph-enterprise-knowledge-graph-swagger-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
