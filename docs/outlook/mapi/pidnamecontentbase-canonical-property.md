---
title: "PidNameContentBase Canonical Property"
 
 
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- PidNameContentBase
api_type:
- COM
ms.assetid: ab197ace-6e7d-4ec5-9f6d-4a63a1eda11c
description: "Contains an RFC3282 Content-Base header field value. To set the value, MIME clients must write the value to a Content-Base header field on a MIME entity to message body."
---

# PidNameContentBase Canonical Property

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Contains an [RFC3282] Content-Base header field value.
  
|Property |Value |
|:-----|:-----|
|Friendly names:  <br/> |BodyContentBase  <br/> |
|Property set:  <br/> |PS_INTERNET_HEADERS  <br/> |
|Property name:  <br/> |Content-Base  <br/> |
|Data type:  <br/> |PT_UNICODE  <br/> |
|Area:  <br/> |Email  <br/> |
   
## Remarks

To set the value of this property, Multipurpose Internet Message Extensions (MIME) clients must write the desired value to a Content-Base header field on a MIME entity that maps to a message body. MIME readers must copy the value of a Content-Base header field on such a MIME entity to the value of this property.
  
## Related resources

### Protocol specifications

[[MS-OXPROPS]](https://msdn.microsoft.com/library/f6ab1613-aefe-447d-a49c-18217230b148%28Office.15%29.aspx)
  
> Provides property set definitions and references to related Exchange Server protocol specifications.
    
[[MS-OXCMAIL]](https://msdn.microsoft.com/library/b60d48db-183f-4bf5-a908-f584e62cb2d4%28Office.15%29.aspx)
  
> Converts from Internet standard email conventions to message objects.
    
### Header files

Mapidefs.h
  
> Provides data type definitions.
    
## See also



[MAPI Properties](mapi-properties.md)
  
[MAPI Canonical Properties](mapi-canonical-properties.md)
  
[Mapping Canonical Property Names to MAPI Names](mapping-canonical-property-names-to-mapi-names.md)
  
[Mapping MAPI Names to Canonical Property Names](mapping-mapi-names-to-canonical-property-names.md)

