---
title: "Update filterOperatorSchema"
description: "Update the properties of a filterOperatorSchema object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update filterOperatorSchema
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of a [filterOperatorSchema](../resources/synchronization-filteroperatorschema.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
PATCH /filterOperators/{filterOperatorsId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [filterOperatorSchema](../resources/synchronization-filteroperatorschema.md) object.

The following table shows the properties that are required when you update the [filterOperatorSchema](../resources/synchronization-filteroperatorschema.md).

|Property|Type|Description|
|:---|:---|:---|
|name|String|**TODO: Add Description**|
|arity|scopeOperatorType|**TODO: Add Description**. Possible values are: `Binary`, `Unary`.|
|multivaluedComparisonType|scopeOperatorMultiValuedComparisonType|**TODO: Add Description**. Possible values are: `All`, `Any`.|
|supportedAttributeTypes|attributeType collection|**TODO: Add Description**. Possible values are: `String`, `Integer`, `Reference`, `Binary`, `Boolean`, `DateTime`.|



## Response

If successful, this method returns a `200 OK` response code and an updated [filterOperatorSchema](../resources/synchronization-filteroperatorschema.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_filteroperatorschema"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/filterOperators/{filterOperatorsId}
Content-Type: application/json
Content-length: 199

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


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

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

