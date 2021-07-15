---
title: "filterOperatorSchema resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# filterOperatorSchema resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List filterOperatorSchemas](../api/synchronization-filteroperatorschema-list.md)|[filterOperatorSchema](../resources/synchronization-filteroperatorschema.md) collection|Get a list of the [filterOperatorSchema](../resources/synchronization-filteroperatorschema.md) objects and their properties.|
|[Create filterOperatorSchema](../api/synchronization-filteroperatorschema-post-filteroperators.md)|[filterOperatorSchema](../resources/synchronization-filteroperatorschema.md)|Create a new [filterOperatorSchema](../resources/synchronization-filteroperatorschema.md) object.|
|[Get filterOperatorSchema](../api/synchronization-filteroperatorschema-get.md)|[filterOperatorSchema](../resources/synchronization-filteroperatorschema.md)|Read the properties and relationships of a [filterOperatorSchema](../resources/synchronization-filteroperatorschema.md) object.|
|[Update filterOperatorSchema](../api/synchronization-filteroperatorschema-update.md)|[filterOperatorSchema](../resources/synchronization-filteroperatorschema.md)|Update the properties of a [filterOperatorSchema](../resources/synchronization-filteroperatorschema.md) object.|
|[Delete filterOperatorSchema](../api/synchronization-filteroperatorschema-delete.md)|None|Deletes a [filterOperatorSchema](../resources/synchronization-filteroperatorschema.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|arity|scopeOperatorType|**TODO: Add Description**. Possible values are: `Binary`, `Unary`.|
|multivaluedComparisonType|scopeOperatorMultiValuedComparisonType|**TODO: Add Description**. Possible values are: `All`, `Any`.|
|name|String|**TODO: Add Description**|
|supportedAttributeTypes|attributeType collection|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.filterOperatorSchema",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.filterOperatorSchema",
  "name": "String",
  "arity": "String",
  "multivaluedComparisonType": "String",
  "supportedAttributeTypes": [
    "String"
  ]
}
```

