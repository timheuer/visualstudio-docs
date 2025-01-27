---
description: "Retrieves the one-based source line number where the statement or expression ends."
title: "IDiaLineNumber::get_lineNumberEnd"
ms.date: "11/04/2016"
ms.topic: "reference"
dev_langs:
  - "C++"
helpviewer_keywords:
  - "IDiaLineNumber::get_lineNumberEnd method"
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
---
# IDiaLineNumber::get_lineNumberEnd

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Retrieves the one-based source line number where the statement or expression ends.

## Syntax

```C++
HRESULT get_lineNumberEnd ( 
   DWORD* pRetVal
);
```

#### Parameters
 `pRetVal`

[out] Returns the line number where the statement or expression ends. If the value is zero, then the end information is not present.

## Return Value
 If successful, returns `S_OK`. Returns `S_FALSE` if this property is not supported. Otherwise, returns an error code.

## See also
- [IDiaLineNumber](../../debugger/debug-interface-access/idialinenumber.md)
