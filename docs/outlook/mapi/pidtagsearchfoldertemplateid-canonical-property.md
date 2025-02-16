---
title: "PidTagSearchFolderTemplateId Canonical Property"
 
 
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- MAPI.PidTagSearchFolderTemplateId
api_type:
- COM
ms.assetid: 56288f55-b3ba-42df-9c90-f9b5857f19a1
description: "Contains the ID of the template that is being used for the search. This property on the message defines the search folder identifies its corresponding template."
---

# PidTagSearchFolderTemplateId Canonical Property

**Applies to**: Outlook 2013 | Outlook 2016
  
Contains the ID of the template that is being used for the search.
  
|Property |Value |
|:-----|:-----|
|Associated properties:  <br/> |PR_WB_SF_TEMPLATE_ID  <br/> |
|Identifier:  <br/> |0x6841  <br/> |
|Data type:  <br/> |PT_LONG  <br/> |
|Area:  <br/> |Search  <br/> |

## Remarks

Search folder criteria is specified by a template. This property on the message that defines the search folder identifies its corresponding template. In addition to defining search criteria, a template also defines folders to exclude from the search, defines items to exclude from the search, and specifies the value of **PR_WB_SF_STORAGE_TYPE** ([PidTagSearchFolderStorageType](pidtagsearchfolderstoragetype-canonical-property.md)).
  
For more information about Search Folder Templates see [[MS-OXOSRCH]](https://msdn.microsoft.com/library/c72e49b8-78c7-4483-ad65-e46e9133673b%28Office.15%29.aspx).
  
## Related resources

### Protocol specifications

[[MS-OXPROPS]](https://msdn.microsoft.com/library/f6ab1613-aefe-447d-a49c-18217230b148%28Office.15%29.aspx)
  
> Provides references to related Exchange Server protocol specifications.

[[MS-OXOSRCH]](https://msdn.microsoft.com/library/c72e49b8-78c7-4483-ad65-e46e9133673b%28Office.15%29.aspx)
  
> Specifies the properties and operations for manipulating a search folder list configuration.

### Header files

Mapidefs.h
  
> Provides data type definitions.

Mapitags.h
  
> Contains definitions of properties listed as alternate names.

## See also

[MAPI Properties](mapi-properties.md)  
[MAPI Canonical Properties](mapi-canonical-properties.md)  
[Mapping Canonical Property Names to MAPI Names](mapping-canonical-property-names-to-mapi-names.md)  
[Mapping MAPI Names to Canonical Property Names](mapping-mapi-names-to-canonical-property-names.md)
