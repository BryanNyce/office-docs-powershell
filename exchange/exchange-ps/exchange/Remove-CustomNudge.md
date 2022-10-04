---
external help file: Microsoft.Exchange.Management.RestApiClient.dll-Help.xml
Module Name: ExchangeOnlineManagement
online version: https://learn.microsoft.com/powershell/module/exchange/remove-customnudge
applicable: Exchange Online
title: Remove-CustomNudge
schema: 2.0.0
author: chrisda
ms.author: chrisda
ms.reviewer: shusun
---

# Remove-CustomNudge

## SYNOPSIS
This cmdlet is available only in the Exchange Online PowerShell module v2.0.6-Preview5 or later. For more information, see [About the Exchange Online PowerShell module](https://aka.ms/exov3-module).

**Note**: The features that are associated with this cmdlet are currently in Preview, are not available in all organizations, and are subject to change. Access to the cmdlet does not guarantee access to the feature.

Use the Remove-CustomNudge cmdlet to remove Custom Nudges that are displayed in user Briefing email messages.

For information about the parameter sets in the Syntax section below, see [Exchange cmdlet syntax](https://learn.microsoft.com/powershell/exchange/exchange-cmdlet-syntax).

## SYNTAX

```
Remove-CustomNudge -Name <String>
 [-ResultSize <Unlimited>]
 [<CommonParameters>]
```

## DESCRIPTION
This cmdlet requires the .NET Framework 4.7.2 or later. To run this cmdlet, you need to be a member of one of the following roles in Azure Active Directory:

- Global Administrator
- Exchange Administrator
- Insights Administrator

To learn more about administrator role permissions in Azure Active Directory, see [Azure AD built-in roles](https://learn.microsoft.com/azure/active-directory/roles/permissions-reference).

## EXAMPLES

### Example 1
```powershell
Remove-CustomNudge -Name perfReviewNudge
```

This example removes the existing Custom Nudge named "perfReviewNudge".

## PARAMETERS

### -Name
The Name parameter specifies the name of the Custom Nudge that you want to remove. If the value contains spaces, enclose the value in quotation marks (").

```yaml
Type: String
Parameter Sets: (All)
Aliases:
Applicable: Exchange Online

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ResultSize
This parameter is reserved for internal Microsoft use.

```yaml
Type: Unlimited
Parameter Sets: (All)
Aliases:
Applicable: Exchange Online

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](https://go.microsoft.com/fwlink/p/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS
