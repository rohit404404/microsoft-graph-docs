---
title: "accessPackageCatalog resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# accessPackageCatalog resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List accessPackageCatalogs](../api/accesspackagecatalog-list.md)|[accessPackageCatalog](../resources/accesspackagecatalog.md) collection|Get a list of the [accessPackageCatalog](../resources/accesspackagecatalog.md) objects and their properties.|
|[Create accessPackageCatalog](../api/accesspackagecatalog-create.md)|[accessPackageCatalog](../resources/accesspackagecatalog.md)|Create a new [accessPackageCatalog](../resources/accesspackagecatalog.md) object.|
|[Get accessPackageCatalog](../api/accesspackagecatalog-get.md)|[accessPackageCatalog](../resources/accesspackagecatalog.md)|Read the properties and relationships of an [accessPackageCatalog](../resources/accesspackagecatalog.md) object.|
|[Update accessPackageCatalog](../api/accesspackagecatalog-update.md)|[accessPackageCatalog](../resources/accesspackagecatalog.md)|Update the properties of an [accessPackageCatalog](../resources/accesspackagecatalog.md) object.|
|[Delete accessPackageCatalog](../api/accesspackagecatalog-delete.md)|None|Deletes an [accessPackageCatalog](../resources/accesspackagecatalog.md) object.|
|[List accessPackageResourceRoles](../api/accesspackagecatalog-list-accesspackageresourceroles.md)|[accessPackageResourceRole](../resources/accesspackageresourcerole.md) collection|Get the accessPackageResourceRole resources from the accessPackageResourceRoles navigation property.|
|[Create accessPackageResourceRole](../api/accesspackagecatalog-post-accesspackageresourceroles.md)|[accessPackageResourceRole](../resources/accesspackageresourcerole.md)|Create a new accessPackageResourceRole object.|
|[List accessPackageResources](../api/accesspackagecatalog-list-accesspackageresources.md)|[accessPackageResource](../resources/accesspackageresource.md) collection|Get the accessPackageResource resources from the accessPackageResources navigation property.|
|[Create accessPackageResource](../api/accesspackagecatalog-post-accesspackageresources.md)|[accessPackageResource](../resources/accesspackageresource.md)|Create a new accessPackageResource object.|
|[List accessPackageResourceScopes](../api/accesspackagecatalog-list-accesspackageresourcescopes.md)|[accessPackageResourceScope](../resources/accesspackageresourcescope.md) collection|Get the accessPackageResourceScope resources from the accessPackageResourceScopes navigation property.|
|[Create accessPackageResourceScope](../api/accesspackagecatalog-post-accesspackageresourcescopes.md)|[accessPackageResourceScope](../resources/accesspackageresourcescope.md)|Create a new accessPackageResourceScope object.|
|[List accessPackages](../api/accesspackagecatalog-list-accesspackages.md)|[accessPackage](../resources/accesspackage.md) collection|Get the accessPackage resources from the accessPackages navigation property.|
|[Create accessPackage](../api/accesspackagecatalog-post-accesspackages.md)|[accessPackage](../resources/accesspackage.md)|Create a new accessPackage object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|catalogStatus|String|**TODO: Add Description**|
|catalogType|String|**TODO: Add Description**|
|createdBy|String|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|isExternallyVisible|Boolean|**TODO: Add Description**|
|modifiedBy|String|**TODO: Add Description**|
|modifiedDateTime|DateTimeOffset|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|accessPackageResourceRoles|[accessPackageResourceRole](../resources/accesspackageresourcerole.md) collection|**TODO: Add Description**|
|accessPackageResources|[accessPackageResource](../resources/accesspackageresource.md) collection|**TODO: Add Description**|
|accessPackageResourceScopes|[accessPackageResourceScope](../resources/accesspackageresourcescope.md) collection|**TODO: Add Description**|
|accessPackages|[accessPackage](../resources/accesspackage.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.accessPackageCatalog",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.accessPackageCatalog",
  "id": "String (identifier)",
  "displayName": "String",
  "description": "String",
  "catalogType": "String",
  "catalogStatus": "String",
  "isExternallyVisible": "Boolean",
  "createdBy": "String",
  "createdDateTime": "String (timestamp)",
  "modifiedBy": "String",
  "modifiedDateTime": "String (timestamp)"
}
```

