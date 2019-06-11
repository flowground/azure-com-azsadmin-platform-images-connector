# ![LOGO](logo.png) Compute Admin Client **flow**ground Connector

## Description

A generated **flow**ground connector for the Compute Admin Client API (version 2015-12-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-PlatformImages/2015-12-01-preview/swagger.json<br/>
Generated at: 2019-06-11T18:13:40+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns all platform images.

> Returns a list of all platform images.

*Tags:* `PlatformImages`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Location of the resource.
* `api-version` - _required_ - Client API Version.

### Deletes a platform image matching publisher, offer, skus and version

> Delete a platform image

*Tags:* `PlatformImages`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Location of the resource.
* `publisher` - _required_ - Name of the publisher.
* `offer` - _required_ - Name of the offer.
* `sku` - _required_ - Name of the SKU.
* `version` - _required_ - The version of the resource.
* `api-version` - _required_ - Client API Version.

### Returns the requested platform image.

> Returns the specific platform image matching publisher, offer, skus and version.

*Tags:* `PlatformImages`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Location of the resource.
* `publisher` - _required_ - Name of the publisher.
* `offer` - _required_ - Name of the offer.
* `sku` - _required_ - Name of the SKU.
* `version` - _required_ - The version of the resource.
* `api-version` - _required_ - Client API Version.

### Creates a platform image.

> Creates a new platform image with given publisher, offer, skus and version.

*Tags:* `PlatformImages`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Location of the resource.
* `publisher` - _required_ - Name of the publisher.
* `offer` - _required_ - Name of the offer.
* `sku` - _required_ - Name of the SKU.
* `version` - _required_ - The version of the resource.
* `api-version` - _required_ - Client API Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-platform-images-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
