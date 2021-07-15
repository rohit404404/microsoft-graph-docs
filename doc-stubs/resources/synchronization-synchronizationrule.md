---
title: "synchronizationRule resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# synchronizationRule resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|editable|Boolean|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|metadata|[stringKeyStringValuePair](../resources/synchronization-stringkeystringvaluepair.md) collection|**TODO: Add Description**|
|name|String|**TODO: Add Description**|
|objectMappings|[objectMapping](../resources/synchronization-objectmapping.md) collection|**TODO: Add Description**|
|priority|Int32|**TODO: Add Description**|
|sourceDirectoryName|String|**TODO: Add Description**|
|targetDirectoryName|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.synchronizationRule"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.synchronizationRule",
  "editable": "Boolean",
  "id": "String (identifier)",
  "metadata": [
    {
      "@odata.type": "microsoft.graph.stringKeyStringValuePair"
    }
  ],
  "name": "String",
  "objectMappings": [
    {
      "@odata.type": "microsoft.graph.objectMapping"
    }
  ],
  "priority": "Integer",
  "sourceDirectoryName": "String",
  "targetDirectoryName": "String"
}
```

