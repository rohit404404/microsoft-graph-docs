---
title: "synchronizationSchema resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# synchronizationSchema resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List synchronizationSchemas](../api/synchronization-synchronizationschema-list.md)|[synchronizationSchema](../resources/synchronization-synchronizationschema.md) collection|Get a list of the [synchronizationSchema](../resources/synchronization-synchronizationschema.md) objects and their properties.|
|[Create synchronizationSchema](../api/synchronization-synchronizationschema-create.md)|[synchronizationSchema](../resources/synchronization-synchronizationschema.md)|Create a new [synchronizationSchema](../resources/synchronization-synchronizationschema.md) object.|
|[Get synchronizationSchema](../api/synchronization-synchronizationschema-get.md)|[synchronizationSchema](../resources/synchronization-synchronizationschema.md)|Read the properties and relationships of a [synchronizationSchema](../resources/synchronization-synchronizationschema.md) object.|
|[Update synchronizationSchema](../api/synchronization-synchronizationschema-update.md)|[synchronizationSchema](../resources/synchronization-synchronizationschema.md)|Update the properties of a [synchronizationSchema](../resources/synchronization-synchronizationschema.md) object.|
|[Delete synchronizationSchema](../api/synchronization-synchronizationschema-delete.md)|None|Deletes a [synchronizationSchema](../resources/synchronization-synchronizationschema.md) object.|
|[List directories](../api/synchronization-synchronizationschema-list-directories.md)|[directoryDefinition](../resources/synchronization-directorydefinition.md) collection|Get the directoryDefinition resources from the directories navigation property.|
|[Create directoryDefinition](../api/synchronization-synchronizationschema-post-directories.md)|[directoryDefinition](../resources/synchronization-directorydefinition.md)|Create a new directoryDefinition object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|synchronizationRules|[synchronizationRule](../resources/synchronization-synchronizationrule.md) collection|**TODO: Add Description**|
|version|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|directories|[directoryDefinition](../resources/synchronization-directorydefinition.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.synchronizationSchema",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.synchronizationSchema",
  "id": "String (identifier)",
  "synchronizationRules": [
    {
      "@odata.type": "microsoft.graph.synchronizationRule"
    }
  ],
  "version": "String"
}
```

