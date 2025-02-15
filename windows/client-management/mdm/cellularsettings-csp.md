---
title: CellularSettings CSP
description: Learn how the CellularSettings configuration service provider is used to configure cellular settings on a mobile device.
ms.assetid: ce8b6f16-37ca-4aaf-98b0-306d12e326df
ms.reviewer: 
manager: dansimp
ms.author: dansimp
ms.topic: article
ms.prod: w10
ms.technology: windows
author: dansimp
ms.date: 06/26/2017
---

# CellularSettings CSP

The CellularSettings configuration service provider is used to configure cellular settings on a mobile device.

> [!Note]
> Starting in Windows 10, version 1703 the CellularSettings CSP is supported in Windows 10 Home, Pro, Enterprise, and Education editions.

The following shows the CellularSettings CSP in tree format as used by Open Mobile Alliance Client Provisioning (OMA CP). The OMA DM protocol isn't supported with this configuration service provider.

```console
./Vendor/MSFT
CellularSettings
----DataRoam
```

<a href="" id="dataroam"></a>**DataRoam**  
<p> Optional. Integer. Specifies the default roaming value. Valid values are:</p>

|Value|Setting|
|--- |--- |
|0|Don’t roam|
|1|Don’t roam (or Domestic roaming if applicable)|
|2|Roam|

## Related topics

[Configuration service provider reference](configuration-service-provider-reference.md)
