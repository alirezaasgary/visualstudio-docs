---
description: "IDiaStackFrame::get_lengthParams retrieves the number of bytes of parameters pushed on the stack."
title: "IDiaStackFrame::get_lengthParams | Microsoft Docs"
ms.date: "11/04/2016"
ms.topic: "reference"
dev_langs:
  - "C++"
helpviewer_keywords:
  - "IDiaStackFrame::get_lengthParams method"
ms.assetid: 78005efa-2883-4823-b4e4-711a66672c78
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
ms.workload:
  - "multiple"
---
# IDiaStackFrame::get_lengthParams

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Retrieves the number of bytes of parameters pushed on the stack.

## Syntax

```C++
HRESULT get_lengthParams ( 
   DWORD* pRetVal
);
```

#### Parameters
 `pRetVal`

[out] Returns the number of bytes of parameters.

## Return Value
 If successful, returns `S_OK`. Returns `S_FALSE` if the property is not supported. Otherwise, returns an error code.

## See also
- [IDiaStackFrame](../../debugger/debug-interface-access/idiastackframe.md)
