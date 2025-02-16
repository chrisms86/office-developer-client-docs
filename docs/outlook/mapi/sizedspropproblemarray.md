---
title: "SizedSPropProblemArray"
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- MAPI.SizedSPropProblemArray
api_type:
- COM
ms.assetid: 2fc3febb-8c69-4315-a112-a28eee98013d
description: "Last modified: March 09, 2015"
---

# SizedSPropProblemArray

**Applies to**: Outlook 2013 | Outlook 2016 
  
Creates a named [SPropProblemArray](spropproblemarray.md) structure that contains a specified number of [SPropProblem](spropproblem.md) structures. 
  
|Property |Value |
|:-----|:-----|
|Header file:  <br/> |Mapidefs.h  <br/> |
|Related structure:  <br/> |**SPropProblemArray** <br/> |
   
```cpp
SizedSPropProblemArray(_cprob, _name)
```

## Parameters

__cprob_
  
> Count of **SPropProblem** structures to be included in the new structure. 
    
__name_
  
> Name for the new structure.
    
## Remarks

Use the **SizedSPropProblemArray** macro to create a property problem array with explicit bounds. To use the new structure that results from the **SizedSPropProblemArray** macro as a pointer to an **SPropProblemArray** structure, perform the following cast: 
  
```cpp
lpPropProbArray = (LPSPropProblemArray) &SizedSPropProblemArray;
```

## See also

- [SPropProblemArray](spropproblemarray.md)
- [SPropProblem](spropproblem.md)
- [Macros Related to Structures](macros-related-to-structures.md)

