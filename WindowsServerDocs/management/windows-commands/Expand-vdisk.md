---
title: Expand vdisk
description: "Windows Commands"
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 3ae547b4-3813-4b86-bacd-bc273c028a2a
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---

# Expand vdisk

>Applies To: Windows Server&reg; 2016, Windows Server&reg; 2012 R2, Windows Server&reg; 2012

Expands a virtual hard disk (VHD) to the size that you specify.
> [!NOTE]
> This command is only applicable to Windows 7 and Windows Server 2008 R2.
## Syntax
```
expand vdisk maximum=<n>
```
## Parameters
|Parameter|Description|
|-------------|---------------|
|maximum=<n>|Specifies the new size for the VHD in megabytes (MB).|
## Remarks
-   A VHD must be selected and detached for this operation to succeed. Use the **select vdisk** command to select a volume and shift the focus to it.
## <a name="BKMK_Examples"></a>Examples
To expand the selected VHD to 20 GB, type:
```
expand vdisk maximum=20000
```
## Additional references
-   [Command-Line Syntax Key](Command-Line-Syntax-Key.md)
-   [Attach vdisk](Attach-vdisk.md)
-   [Compact vdisk](Compact-vdisk.md)

-   [Detach vdisk](Detach-vdisk.md)
-   [Detail vdisk](Detail-vdisk.md)
-   [Merge vdisk](Merge-vdisk.md)
-   [Select vdisk](Select-vdisk.md)
-   [List_1](List_1.md)