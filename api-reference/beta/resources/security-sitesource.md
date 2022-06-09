---
title: "siteSource resource type"
description: ""The container for a site associated with a custodian."
author: "SeunginLyu"
ms.localizationpriority: medium
ms.prod: "ediscovery"
doc_type: resourcePageType
---

# siteSource resource type

Namespace: microsoft.graph.security

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]
The container for a site associated with a custodian.

IInherits from [dataSource](../resources/security-datasource.md).


## Methods
None.
## Properties
|Property|Type|Description|
|:---|:---|:---|
|createdBy|[identitySet](../resources/identityset.md)|The user who created the **siteSource**.|
|createdDateTime|DateTimeOffset|The date and time the **siteSource** was created.|
|displayName|String|The display name of the **siteSource**. This will be the name of the SharePoint site.|
|id|String| The ID of the **siteSource**. The site source can be retrieved at any time with [Get site](../api/site-get.md) - https://graph.microsoft.com/v1.0/sites/{siteId}|
|holdStatus|String|The hold status of the **siteSource**.The possible values are: `notApplied`, `applied`, `applying`, `removing`, `partial`|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|site|[site](../resources/site.md)|The SharePoint site associated with the **siteSource**.|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.security.siteSource",
  "baseType": "microsoft.graph.ediscovery.dataSource",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.security.siteSource",
  "id": "String (identifier)",
  "displayName": "String",
  "holdStatus": "String",
  "createdDateTime": "String (timestamp)",
  "createdBy": {
    "@odata.type": "microsoft.graph.identitySet"
  }
}
```

