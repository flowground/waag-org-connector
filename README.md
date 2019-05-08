# ![LOGO](logo.png) CitySDK Linked Data **flow**ground Connector

## Description

A generated **flow**ground connector for the CitySDK Linked Data API (version v1).

Generated from: https://api.apis.guru/v2/specs/waag.org/v1/swagger.json<br/>
Generated at: 2019-05-07T17:44:47+03:00

## API Description

An API for the distribution and annotation of open data, for small cities and big metropolitan areas.

## Authorization

This API does not require authorization.

## Actions

### Return all layers

*Tags:* `layers`

### Create new layer

*Tags:* `layers`

### Delete a layer

*Tags:* `layers`

#### Input Parameters
* `layer` - _required_

### Return single layer

*Tags:* `layers`

#### Input Parameters
* `layer` - _required_

### Edit a layer

*Tags:* `layers`

#### Input Parameters
* `layer` - _required_

### Return JSON-LD context of single layer

*Tags:* `layers`

#### Input Parameters
* `layer` - _required_

### Overwrite JSON-LD context of single layer

*Tags:* `layers`

#### Input Parameters
* `layer` - _required_

### Return all fields of single layer

*Tags:* `layers`

#### Input Parameters
* `layer` - _required_

### Create new field for single layer

*Tags:* `layers`

#### Input Parameters
* `layer` - _required_

### Delete a single field on single layer

*Tags:* `layers`

#### Input Parameters
* `layer` - _required_
* `field` - _required_

### Return single field of single layer

*Tags:* `layers`

#### Input Parameters
* `layer` - _required_
* `field` - _required_

### Edit single field on single layer

*Tags:* `layers`

#### Input Parameters
* `layer` - _required_
* `field` - _required_

### Overwrite single field on single layer

*Tags:* `layers`

#### Input Parameters
* `layer` - _required_
* `field` - _required_

### Delete all objects from a single layer

*Tags:* `layers`

#### Input Parameters
* `layer` - _required_

### Return all objects with data on single layer

*Tags:* `layers`

#### Input Parameters
* `layer` - _required_

### Edit one or more objects and data on single layer

*Tags:* `layers`

#### Input Parameters
* `layer` - _required_

### Create one or more objects with data on single layer, or add data to existing objects (or a combination thereof)

*Tags:* `layers`

#### Input Parameters
* `layer` - _required_

### Return metadata of single layer about single object, e.g. the date the data was added/modified, etc.

*Tags:* `layers`

#### Input Parameters
* `layer` - _required_
* `cdk_id` - _required_

### Return all owners associated with single layer

*Tags:* `layers`

#### Input Parameters
* `layer` - _required_

### Return single context entity

*Tags:* `ngsi10`

#### Input Parameters
* `entity` - _required_

### Update attributes for single context entity

*Tags:* `ngsi10`

#### Input Parameters
* `entity` - _required_

### Return single context entity attribute

*Tags:* `ngsi10`

#### Input Parameters
* `entity` - _required_
* `attribute` - _required_

### Return objects of particular type

*Tags:* `ngsi10`

#### Input Parameters
* `cetype` - _required_

### Return objects of particular type

*Tags:* `ngsi10`

#### Input Parameters
* `cetype` - _required_
* `attribute` - _required_

### Query context broker for contextElements

*Tags:* `ngsi10`

### Create a new context subscription

*Tags:* `ngsi10`

### Delete a context subscription

*Tags:* `ngsi10`

### Add or update NGSI contextElements

*Tags:* `ngsi10`

### Update/edit a context subscription

*Tags:* `ngsi10`

### Return all objects

*Tags:* `objects`

### Delete a single object

*Tags:* `objects`

#### Input Parameters
* `cdk_id` - _required_

### Get a single object

*Tags:* `objects`

#### Input Parameters
* `cdk_id` - _required_

### Edit a single object

*Tags:* `objects`

#### Input Parameters
* `cdk_id` - _required_

### Get all layers that contain data of single object

*Tags:* `objects`

#### Input Parameters
* `cdk_id` - _required_

### Remove data on layer from single object

*Tags:* `objects`

#### Input Parameters
* `cdk_id` - _required_
* `layer` - _required_

### Return all data on single layer of single object

*Tags:* `objects`

#### Input Parameters
* `cdk_id` - _required_
* `layer` - _required_

### Update data on layer to single object

*Tags:* `objects`

#### Input Parameters
* `cdk_id` - _required_
* `layer` - _required_

### Add data on layer to single object

*Tags:* `objects`

#### Input Parameters
* `cdk_id` - _required_
* `layer` - _required_

### Overwrite data on layer to single object

*Tags:* `objects`

#### Input Parameters
* `cdk_id` - _required_
* `layer` - _required_

### Return all owners

*Tags:* `owners`

### Create new owner

*Tags:* `owners`

### Delete owner - and all layers and data belonging to this owner

*Tags:* `owners`

#### Input Parameters
* `owner` - _required_

### Get a single owner

*Tags:* `owners`

#### Input Parameters
* `owner` - _required_

### Edit an owner

*Tags:* `owners`

#### Input Parameters
* `owner` - _required_

### Return all layers belonging to a single owner

*Tags:* `owners`

#### Input Parameters
* `owner` - _required_

### Close session

*Tags:* `session`

### Return a session key

*Tags:* `session`

#### Input Parameters
* `name` - _required_ - Login name.
* `password` - _required_ - Login password.

## License

**flow**ground :- Telekom iPaaS / waag-org-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
