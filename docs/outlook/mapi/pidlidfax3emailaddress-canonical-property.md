---
title: "PidLidFax3EmailAddress Canonical Property"
 
 
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- PidLidFax3EmailAddress
api_type:
- COM
ms.assetid: 8b53c307-1a01-4c94-b6db-9fcb840ce390
description: "Specifies the email address of the contact's other fax address. This property should contain a display name, the @ character, and a fax number."
---

# PidLidFax3EmailAddress Canonical Property

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Specifies the email address of the contact's other fax address.
  
|Property |Value |
|:-----|:-----|
|Associated properties:  <br/> |dispidFax3EmailAddress  <br/> |
|Property set:  <br/> |PSETID_Address  <br/> |
|Long ID (LID):  <br/> |0x000080D3  <br/> |
|Data type:  <br/> |PT_UNICODE  <br/> |
|Area:  <br/> |Contact  <br/> |
   
## Remarks

This property, if present, should contain a user-readable display name, followed by the "@" character, followed by a fax number.
  
## Related resources

### Protocol specifications

[[MS-OXPROPS]](https://msdn.microsoft.com/library/f6ab1613-aefe-447d-a49c-18217230b148%28Office.15%29.aspx)
  
> Provides property set definitions and references to related Exchange Server protocol specifications.
    
[[MS-OXOCNTC]](https://msdn.microsoft.com/library/9b636532-9150-4836-9635-9c9b756c9ccf%28Office.15%29.aspx)
  
> Specifies the properties and operations that are permissible for contacts and personal distribution lists.
    
### Header files

Mapidefs.h
  
> Provides data type definitions.
    
## See also



[MAPI Properties](mapi-properties.md)
  
[MAPI Canonical Properties](mapi-canonical-properties.md)
  
[Mapping Canonical Property Names to MAPI Names](mapping-canonical-property-names-to-mapi-names.md)
  
[Mapping MAPI Names to Canonical Property Names](mapping-mapi-names-to-canonical-property-names.md)

