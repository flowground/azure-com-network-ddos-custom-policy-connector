# ![LOGO](logo.png) NetworkManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the NetworkManagementClient API (version 2018-12-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/network-ddosCustomPolicy/2018-12-01/swagger.json<br/>
Generated at: 2019-06-11T18:14:06+03:00

## API Description

The Microsoft Azure Network management API provides a RESTful set of web services that interact with Microsoft Azure Networks service to manage your network resources. The API has entities that capture the relationship between an end user and the Microsoft Azure Networks service.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Deletes the specified DDoS custom policy.

*Tags:* `ddosCustomPolicies`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `ddosCustomPolicyName` - _required_ - The name of the DDoS custom policy.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets information about the specified DDoS custom policy.

*Tags:* `ddosCustomPolicies`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `ddosCustomPolicyName` - _required_ - The name of the DDoS custom policy.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Update a DDoS custom policy tags

*Tags:* `ddosCustomPolicies`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `ddosCustomPolicyName` - _required_ - The name of the DDoS custom policy.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a DDoS custom policy.

*Tags:* `ddosCustomPolicies`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `ddosCustomPolicyName` - _required_ - The name of the DDoS custom policy.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-network-ddos-custom-policy-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
