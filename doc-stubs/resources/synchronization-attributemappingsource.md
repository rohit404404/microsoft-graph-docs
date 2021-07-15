---
title: "attributeMappingSource resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# attributeMappingSource resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|expression|String|**TODO: Add Description**|
|name|String|**TODO: Add Description**|
|parameters|[stringKeyAttributeMappingSourceValuePair](../resources/synchronization-stringkeyattributemappingsourcevaluepair.md) collection|**TODO: Add Description**|
|type|attributeMappingSourceType|**TODO: Add Description**. Possible values are: `Attribute`, `Constant`, `Function`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.attributeMappingSource"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.attributeMappingSource",
  "expression": "String",
  "name": "String",
  "parameters": [
    {
      "@odata.type": "microsoft.graph.stringKeyAttributeMappingSourceValuePair"
    }
  ],
  "type": "String"
}
```

