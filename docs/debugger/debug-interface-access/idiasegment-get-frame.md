---
description: "Retrieves the segment number."
title: "IDiaSegment::get_frame"
ms.date: "11/04/2016"
ms.topic: "reference"
dev_langs:
  - "C++"
helpviewer_keywords:
  - "IDiaSegment::get_frame method"
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
---
# IDiaSegment::get_frame

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Retrieves the segment number.

## Syntax

```C++
HRESULT get_frame ( 
   DWORD* pRetVal
);
```

#### Parameters
 `pRetVal`

[out] Returns the segment number.

## Return Value
 If successful, returns `S_OK`. Returns `S_FALSE` if this property is not supported. Otherwise, returns an error code.

## See also
- [IDiaSegment](../../debugger/debug-interface-access/idiasegment.md)
