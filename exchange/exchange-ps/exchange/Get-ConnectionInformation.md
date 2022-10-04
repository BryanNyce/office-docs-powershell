---
external help file: Microsoft.Exchange.Management.ExoPowershellGalleryModule.dll-Help.xml
Module Name: ExchangeOnlineManagement
online version: https://learn.microsoft.com/powershell/module/exchange/get-connectioninformation
applicable: Exchange Online
title: Get-ConnectionInformation
schema: 2.0.0
author: chrisda
ms.author: chrisda
ms.reviewer:
---

# Get-ConnectionInformation

## SYNOPSIS
This cmdlet is available only in the Exchange Online PowerShell module v2.0.6-Preview7 or later. For more information, see [About the Exchange Online PowerShell module](https://aka.ms/exov3-module).

Use the Get-ConnectionInformation cmdlet to get information about all REST-based connections in the current PowerShell instance with Exchange Online.

For information about the parameter sets in the Syntax section below, see [Exchange cmdlet syntax](https://learn.microsoft.com/powershell/exchange/exchange-cmdlet-syntax).

## SYNTAX

```
Get-ConnectionInformation [<CommonParameters>]
```

## DESCRIPTION
The Get-ConnectionInformation cmdlet returns the information about all active REST-based connections with Exchange Online in the current PowerShell instance. This cmdlet is equivalent to the Get-PSSession cmdlet that's used with remote PowerShell sessions.

## EXAMPLES

### Example 1
```powershell
Get-ConnectionInformation
```

This example returns a list of all active REST-based connections with Exchange Online in the current PowerShell instance.

## PARAMETERS

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](https://go.microsoft.com/fwlink/p/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS
