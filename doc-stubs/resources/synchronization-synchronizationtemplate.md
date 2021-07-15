---
title: "synchronizationTemplate resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# synchronizationTemplate resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List synchronizationTemplates](../api/synchronization-synchronizationtemplate-list.md)|[synchronizationTemplate](../resources/synchronization-synchronizationtemplate.md) collection|Get a list of the [synchronizationTemplate](../resources/synchronization-synchronizationtemplate.md) objects and their properties.|
|[Create synchronizationTemplate](../api/synchronization-synchronizationtemplate-create.md)|[synchronizationTemplate](../resources/synchronization-synchronizationtemplate.md)|Create a new [synchronizationTemplate](../resources/synchronization-synchronizationtemplate.md) object.|
|[Get synchronizationTemplate](../api/synchronization-synchronizationtemplate-get.md)|[synchronizationTemplate](../resources/synchronization-synchronizationtemplate.md)|Read the properties and relationships of a [synchronizationTemplate](../resources/synchronization-synchronizationtemplate.md) object.|
|[Update synchronizationTemplate](../api/synchronization-synchronizationtemplate-update.md)|[synchronizationTemplate](../resources/synchronization-synchronizationtemplate.md)|Update the properties of a [synchronizationTemplate](../resources/synchronization-synchronizationtemplate.md) object.|
|[Delete synchronizationTemplate](../api/synchronization-synchronizationtemplate-delete.md)|None|Deletes a [synchronizationTemplate](../resources/synchronization-synchronizationtemplate.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|applicationId|Guid|**TODO: Add Description**|
|default|Boolean|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|discoverable|Boolean|**TODO: Add Description**|
|factoryTag|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|metadata|[metadataEntry](../resources/synchronization-metadataentry.md) collection|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|schema|[synchronizationSchema](../resources/synchronization-synchronizationschema.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.synchronizationTemplate",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.synchronizationTemplate",
  "id": "String (identifier)",
  "applicationId": "Guid",
  "default": "Boolean",
  "description": "String",
  "discoverable": "Boolean",
  "factoryTag": "String",
  "metadata": [
    {
      "@odata.type": "microsoft.graph.metadataEntry"
    }
  ]
}
```

