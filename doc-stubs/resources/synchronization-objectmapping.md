---
title: "objectMapping resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# objectMapping resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|attributeMappings|[attributeMapping](../resources/synchronization-attributemapping.md) collection|**TODO: Add Description**|
|enabled|Boolean|**TODO: Add Description**|
|flowTypes|objectFlowTypes|**TODO: Add Description**. Possible values are: `None`, `Add`, `Update`, `Delete`.|
|metadata|[metadataEntry](../resources/synchronization-metadataentry.md) collection|**TODO: Add Description**|
|name|String|**TODO: Add Description**|
|scope|[filter](../resources/synchronization-filter.md)|**TODO: Add Description**|
|sourceObjectName|String|**TODO: Add Description**|
|targetObjectName|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.objectMapping"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.objectMapping",
  "attributeMappings": [
    {
      "@odata.type": "microsoft.graph.attributeMapping"
    }
  ],
  "enabled": "Boolean",
  "flowTypes": "String",
  "metadata": [
    {
      "@odata.type": "microsoft.graph.metadataEntry"
    }
  ],
  "name": "String",
  "scope": {
    "@odata.type": "microsoft.graph.filter"
  },
  "sourceObjectName": "String",
  "targetObjectName": "String"
}
```

