---
title: "accessPackage resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# accessPackage resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List accessPackages](../api/accesspackage-list.md)|[accessPackage](../resources/accesspackage.md) collection|Get a list of the [accessPackage](../resources/accesspackage.md) objects and their properties.|
|[Create accessPackage](../api/accesspackage-create.md)|[accessPackage](../resources/accesspackage.md)|Create a new [accessPackage](../resources/accesspackage.md) object.|
|[Get accessPackage](../api/accesspackage-get.md)|[accessPackage](../resources/accesspackage.md)|Read the properties and relationships of an [accessPackage](../resources/accesspackage.md) object.|
|[Update accessPackage](../api/accesspackage-update.md)|[accessPackage](../resources/accesspackage.md)|Update the properties of an [accessPackage](../resources/accesspackage.md) object.|
|[Delete accessPackage](../api/accesspackage-delete.md)|None|Deletes an [accessPackage](../resources/accesspackage.md) object.|
|[List accessPackageAssignmentPolicies](../api/accesspackage-list-accesspackageassignmentpolicies.md)|[accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md) collection|Get the accessPackageAssignmentPolicy resources from the accessPackageAssignmentPolicies navigation property.|
|[Create accessPackageAssignmentPolicy](../api/accesspackage-post-accesspackageassignmentpolicies.md)|[accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md)|Create a new accessPackageAssignmentPolicy object.|
|[List accessPackageResourceRoleScopes](../api/accesspackage-list-accesspackageresourcerolescopes.md)|[accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md) collection|Get the accessPackageResourceRoleScope resources from the accessPackageResourceRoleScopes navigation property.|
|[Create accessPackageResourceRoleScope](../api/accesspackage-post-accesspackageresourcerolescopes.md)|[accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md)|Create a new accessPackageResourceRoleScope object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|catalogId|String|**TODO: Add Description**|
|createdBy|String|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|isHidden|Boolean|**TODO: Add Description**|
|isRoleScopesVisible|Boolean|**TODO: Add Description**|
|modifiedBy|String|**TODO: Add Description**|
|modifiedDateTime|DateTimeOffset|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|accessPackageAssignmentPolicies|[accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md) collection|**TODO: Add Description**|
|accessPackageCatalog|[accessPackageCatalog](../resources/accesspackagecatalog.md)|**TODO: Add Description**|
|accessPackageResourceRoleScopes|[accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.accessPackage",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.accessPackage",
  "id": "String (identifier)",
  "catalogId": "String",
  "displayName": "String",
  "description": "String",
  "isHidden": "Boolean",
  "isRoleScopesVisible": "Boolean",
  "createdBy": "String",
  "createdDateTime": "String (timestamp)",
  "modifiedBy": "String",
  "modifiedDateTime": "String (timestamp)"
}
```

