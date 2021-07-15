---
title: "attributeMappingFunctionSchema resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# attributeMappingFunctionSchema resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List attributeMappingFunctionSchemas](../api/synchronization-attributemappingfunctionschema-list.md)|[attributeMappingFunctionSchema](../resources/synchronization-attributemappingfunctionschema.md) collection|Get a list of the [attributeMappingFunctionSchema](../resources/synchronization-attributemappingfunctionschema.md) objects and their properties.|
|[Create attributeMappingFunctionSchema](../api/synchronization-attributemappingfunctionschema-post-functions.md)|[attributeMappingFunctionSchema](../resources/synchronization-attributemappingfunctionschema.md)|Create a new [attributeMappingFunctionSchema](../resources/synchronization-attributemappingfunctionschema.md) object.|
|[Get attributeMappingFunctionSchema](../api/synchronization-attributemappingfunctionschema-get.md)|[attributeMappingFunctionSchema](../resources/synchronization-attributemappingfunctionschema.md)|Read the properties and relationships of an [attributeMappingFunctionSchema](../resources/synchronization-attributemappingfunctionschema.md) object.|
|[Update attributeMappingFunctionSchema](../api/synchronization-attributemappingfunctionschema-update.md)|[attributeMappingFunctionSchema](../resources/synchronization-attributemappingfunctionschema.md)|Update the properties of an [attributeMappingFunctionSchema](../resources/synchronization-attributemappingfunctionschema.md) object.|
|[Delete attributeMappingFunctionSchema](../api/synchronization-attributemappingfunctionschema-delete.md)|None|Deletes an [attributeMappingFunctionSchema](../resources/synchronization-attributemappingfunctionschema.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|name|String|**TODO: Add Description**|
|parameters|[attributeMappingParameterSchema](../resources/synchronization-attributemappingparameterschema.md) collection|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.attributeMappingFunctionSchema",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.attributeMappingFunctionSchema",
  "name": "String",
  "parameters": [
    {
      "@odata.type": "microsoft.graph.attributeMappingParameterSchema"
    }
  ]
}
```

