---
title: "List accessPackageAssignmentPolicies"
description: "Get a list of the accessPackageAssignmentPolicy objects and their properties."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# List accessPackageAssignmentPolicies
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Get a list of the [accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md) objects and their properties.

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
GET /identityGovernance/entitlementManagement/accessPackageAssignmentPolicies
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a collection of [accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "list_accesspackageassignmentpolicy"
}
-->
``` http
GET https://graph.microsoft.com/beta/identityGovernance/entitlementManagement/accessPackageAssignmentPolicies
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(Microsoft.IGAELM.EC.FrontEnd.ExternalModel.accessPackageAssignmentPolicy)"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": [
    {
      "@odata.type": "#Microsoft.IGAELM.EC.FrontEnd.ExternalModel.accessPackageAssignmentPolicy",
      "id": "da50f6e2-f6e2-da50-e2f6-50dae2f650da",
      "accessPackageId": "String",
      "displayName": "String",
      "description": "String",
      "canExtend": "Boolean",
      "durationInDays": "Integer",
      "expirationDateTime": "String (timestamp)",
      "createdBy": "String",
      "createdDateTime": "String (timestamp)",
      "modifiedBy": "String",
      "modifiedDateTime": "String (timestamp)",
      "questions": [
        {
          "@odata.type": "microsoft.graph.accessPackageMultipleChoiceQuestion"
        }
      ],
      "requestorSettings": {
        "@odata.type": "microsoft.graph.requestorSettings"
      },
      "requestApprovalSettings": {
        "@odata.type": "microsoft.graph.approvalSettings"
      },
      "accessReviewSettings": {
        "@odata.type": "microsoft.graph.assignmentReviewSettings"
      }
    }
  ]
}
```

