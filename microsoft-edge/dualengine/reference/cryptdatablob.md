---
title: DualEngine Win32 C++ CryptDataBlob
description: Represents an SSL Certificate.
author: MSEdgeTeam
ms.author: msedgedevrel
ms.topic: conceptual
ms.service: microsoft-edge
ms.subservice: windows-integration
ms.date: 05/21/2024
keywords: dual engine, dualengine, iemode, win32 apps, win32, edge, ie mode, edge html, CryptDataBlob
topic_type: 
- APIRef
api_name:
- CryptDataBlob
- CryptDataBlob.cbData
- CryptDataBlob.pbData
api_type:
- COM
api_location:
- ieframe.dll
---

# struct CryptDataBlob

> [!IMPORTANT]
> The DualEngine API is part of a Limited Access Feature (see [LimitedAccessFeatures class](/uwp/api/windows.applicationmodel.limitedaccessfeatures)). For more information or 
> to request an unlock token, contact [Microsoft Support](https://go.microsoft.com/fwlink/?linkid=2271232).

Represents an SSL Certificate.

## Summary

 Members                        | Descriptions
--------------------------------|---------------------------------------------
[cbData](#cbdata) | The number of bytes in `pbData`.
[pbData](#pbdata) | A buffer containing a DER-encoded X.509 certificate string.

## Members

#### cbData

The number of bytes in `pbData`.

> public DWORD [cbData](#cbdata)

#### pbData

A buffer containing a DER-encoded X.509 certificate string.

> public BYTE * [pbData](#pbdata)

