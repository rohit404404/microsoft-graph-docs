---
title: "attributeDefinition resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# attributeDefinition resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|anchor|Boolean|**TODO: Add Description**|
|apiExpressions|[stringKeyStringValuePair](../resources/synchronization-stringkeystringvaluepair.md) collection|**TODO: Add Description**|
|caseExact|Boolean|**TODO: Add Description**|
|defaultValue|String|**TODO: Add Description**|
|flowNullValues|Boolean|**TODO: Add Description**|
|metadata|[metadataEntry](../resources/synchronization-metadataentry.md) collection|**TODO: Add Description**|
|multivalued|Boolean|**TODO: Add Description**|
|mutability|mutability|**TODO: Add Description**. Possible values are: `ReadWrite`, `ReadOnly`, `Immutable`, `WriteOnly`.|
|name|String|**TODO: Add Description**|
|referencedObjects|[referencedObject](../resources/synchronization-referencedobject.md) collection|**TODO: Add Description**|
|required|Boolean|**TODO: Add Description**|
|type|attributeType|**TODO: Add Description**. Possible values are: `String`, `Integer`, `Reference`, `Binary`, `Boolean`, `DateTime`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.attributeDefinition"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.attributeDefinition",
  "anchor": "Boolean",
  "apiExpressions": [
    {
      "@odata.type": "microsoft.graph.stringKeyStringValuePair"
    }
  ],
  "caseExact": "Boolean",
  "defaultValue": "String",
  "flowNullValues": "Boolean",
  "metadata": [
    {
      "@odata.type": "microsoft.graph.metadataEntry"
    }
  ],
  "multivalued": "Boolean",
  "mutability": "String",
  "name": "String",
  "required": "Boolean",
  "referencedObjects": [
    {
      "@odata.type": "microsoft.graph.referencedObject"
    }
  ],
  "type": "String"
}
```

