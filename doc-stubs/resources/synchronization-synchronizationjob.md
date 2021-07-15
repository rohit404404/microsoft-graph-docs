---
title: "synchronizationJob resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# synchronizationJob resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List synchronizationJobs](../api/synchronization-synchronizationjob-list.md)|[synchronizationJob](../resources/synchronization-synchronizationjob.md) collection|Get a list of the [synchronizationJob](../resources/synchronization-synchronizationjob.md) objects and their properties.|
|[Create synchronizationJob](../api/synchronization-synchronizationjob-create.md)|[synchronizationJob](../resources/synchronization-synchronizationjob.md)|Create a new [synchronizationJob](../resources/synchronization-synchronizationjob.md) object.|
|[Get synchronizationJob](../api/synchronization-synchronizationjob-get.md)|[synchronizationJob](../resources/synchronization-synchronizationjob.md)|Read the properties and relationships of a [synchronizationJob](../resources/synchronization-synchronizationjob.md) object.|
|[Update synchronizationJob](../api/synchronization-synchronizationjob-update.md)|[synchronizationJob](../resources/synchronization-synchronizationjob.md)|Update the properties of a [synchronizationJob](../resources/synchronization-synchronizationjob.md) object.|
|[Delete synchronizationJob](../api/synchronization-synchronizationjob-delete.md)|None|Deletes a [synchronizationJob](../resources/synchronization-synchronizationjob.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|schedule|[synchronizationSchedule](../resources/synchronization-synchronizationschedule.md)|**TODO: Add Description**|
|status|[synchronizationStatus](../resources/synchronization-synchronizationstatus.md)|**TODO: Add Description**|
|synchronizationJobSettings|[keyValuePair](../resources/synchronization-keyvaluepair.md) collection|**TODO: Add Description**|
|templateId|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|schema|[synchronizationSchema](../resources/synchronization-synchronizationschema.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.synchronizationJob",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.synchronizationJob",
  "id": "String (identifier)",
  "schedule": {
    "@odata.type": "microsoft.graph.synchronizationSchedule"
  },
  "status": {
    "@odata.type": "microsoft.graph.synchronizationStatus"
  },
  "templateId": "String",
  "synchronizationJobSettings": [
    {
      "@odata.type": "microsoft.graph.keyValuePair"
    }
  ]
}
```

