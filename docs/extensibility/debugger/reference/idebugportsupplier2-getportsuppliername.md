---
description: "Gets the port supplier name."
title: IDebugPortSupplier2::GetPortSupplierName
ms.date: 11/04/2016
ms.topic: reference
f1_keywords:
- IDebugPortSupplier2::GetPortSupplierName
helpviewer_keywords:
- IDebugPortSupplier2::GetPortSupplierName
author: maiak
ms.author: maiak
manager: jmartens
ms.technology: vs-ide-debug
dev_langs:
- CPP
- CSharp
---
# IDebugPortSupplier2::GetPortSupplierName

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Gets the port supplier name.

## Syntax

### [C#](#tab/csharp)
```csharp
int GetPortSupplierName( 
   out string pbstrName
);
```
### [C++](#tab/cpp)
```cpp
HRESULT GetPortSupplierName( 
   BSTR* pbstrName
);
```
---

## Parameters
`pbstrName`\
[out] Returns the name of the port supplier.

## Return Value
 If successful, returns `S_OK`; otherwise, returns an error code.

## See also
- [IDebugPortSupplier2](../../../extensibility/debugger/reference/idebugportsupplier2.md)
