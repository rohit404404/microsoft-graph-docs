---
title: "assignmentReviewSettings resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# assignmentReviewSettings resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|durationInDays|Int32|**TODO: Add Description**|
|isEnabled|Boolean|**TODO: Add Description**|
|recurrenceType|String|**TODO: Add Description**|
|reviewers|[userSet](../resources/userset.md) collection|**TODO: Add Description**|
|reviewerType|String|**TODO: Add Description**|
|startDateTime|DateTimeOffset|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.assignmentReviewSettings"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.assignmentReviewSettings",
  "isEnabled": "Boolean",
  "recurrenceType": "String",
  "reviewerType": "String",
  "startDateTime": "String (timestamp)",
  "durationInDays": "Integer",
  "reviewers": [
    {
      "@odata.type": "microsoft.graph.singleUser"
    }
  ]
}
```

