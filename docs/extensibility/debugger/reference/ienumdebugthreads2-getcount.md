---
description: "Returns the number of elements in the threads enumeration."
title: IEnumDebugThreads2::GetCount
ms.date: 11/04/2016
ms.topic: reference
f1_keywords:
- IEnumDebugThreads2::GetCount
helpviewer_keywords:
- IEnumDebugThreads2::GetCount
author: maiak
ms.author: maiak
manager: jmartens
ms.technology: vs-ide-debug
dev_langs:
- CPP
- CSharp
---
# IEnumDebugThreads2::GetCount

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Returns the number of elements in the enumeration.

## Syntax

### [C#](#tab/csharp)
```csharp
int GetCount(
   out uint pcelt
);
```
### [C++](#tab/cpp)
```cpp
HRESULT GetCount(
   ULONG* pcelt
);
```
---

## Parameters
`pcelt`\
[out] Returns the number of elements in the enumeration.

## Return Value
 If successful, returns `S_OK`; otherwise, returns an error code.

## Remarks
 This method is not part of the customary COM enumeration interface which specifies that only the `Next`, `Clone`, `Skip`, and `Reset` methods need to be implemented.

## See also
- [IEnumDebugThreads2](../../../extensibility/debugger/reference/ienumdebugthreads2.md)
