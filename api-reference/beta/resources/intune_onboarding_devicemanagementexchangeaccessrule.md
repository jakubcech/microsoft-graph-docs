﻿# deviceManagementExchangeAccessRule resource type

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://go.microsoft.com/fwlink/?linkid=839381) by the customer.

Device Access Rules in Exchange.
## Properties
|Property|Type|Description|
|---|---|---|
|deviceClass|[deviceManagementExchangeDeviceClass](../resources/intune_onboarding_devicemanagementexchangedeviceclass.md)|Device Class which will be impacted by this rule.|
|accessLevel|String|Access Level for Exchange granted by this rule. Possible values are: `none`, `allow`, `block`, `quarantine`.|

## Relationships
None
## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.deviceManagementExchangeAccessRule"
}
-->
```json
{
  "@odata.type": "#microsoft.graph.deviceManagementExchangeAccessRule",
  "deviceClass": {
    "@odata.type": "microsoft.graph.deviceManagementExchangeDeviceClass",
    "name": "String",
    "type": "String"
  },
  "accessLevel": "String"
}
```


