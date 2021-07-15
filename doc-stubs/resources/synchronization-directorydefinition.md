---
title: "directoryDefinition resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# directoryDefinition resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List directoryDefinitions](../api/synchronization-directorydefinition-list.md)|[directoryDefinition](../resources/synchronization-directorydefinition.md) collection|Get a list of the [directoryDefinition](../resources/synchronization-directorydefinition.md) objects and their properties.|
|[Create directoryDefinition](../api/synchronization-directorydefinition-create.md)|[directoryDefinition](../resources/synchronization-directorydefinition.md)|Create a new [directoryDefinition](../resources/synchronization-directorydefinition.md) object.|
|[Get directoryDefinition](../api/synchronization-directorydefinition-get.md)|[directoryDefinition](../resources/synchronization-directorydefinition.md)|Read the properties and relationships of a [directoryDefinition](../resources/synchronization-directorydefinition.md) object.|
|[Update directoryDefinition](../api/synchronization-directorydefinition-update.md)|[directoryDefinition](../resources/synchronization-directorydefinition.md)|Update the properties of a [directoryDefinition](../resources/synchronization-directorydefinition.md) object.|
|[Delete directoryDefinition](../api/synchronization-directorydefinition-delete.md)|None|Deletes a [directoryDefinition](../resources/synchronization-directorydefinition.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|discoverabilities|directoryDefinitionDiscoverabilities|**TODO: Add Description**. Possible values are: `None`, `AttributeNames`, `AttributeDataTypes`, `AttributeReadOnly`, `ReferenceAttributes`, `UnknownFutureValue`.|
|discoveryDateTime|DateTimeOffset|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|name|String|**TODO: Add Description**|
|objects|[objectDefinition](../resources/synchronization-objectdefinition.md) collection|**TODO: Add Description**|
|readOnly|Boolean|**TODO: Add Description**|
|version|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.directoryDefinition",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.directoryDefinition",
  "id": "String (identifier)",
  "discoveryDateTime": "String (timestamp)",
  "discoverabilities": "String",
  "name": "String",
  "objects": [
    {
      "@odata.type": "microsoft.graph.objectDefinition"
    }
  ],
  "readOnly": "Boolean",
  "version": "String"
}
```

