---
external help file: Microsoft.Rtc.Management.Hosted.dll-help.xml
online version: https://learn.microsoft.com/powershell/module/skype/set-csteamsemergencycallingpolicy
applicable: Microsoft Teams
title: Set-CsTeamsEmergencyCallingPolicy
author: jenstrier
ms.author: jenstr
manager: roykuntz
ms.reviewer: chenc
schema: 2.0.0
---

# Set-CsTeamsEmergencyCallingPolicy

## SYNOPSIS

## SYNTAX

### Identity (Default)
```
Set-CsTeamsEmergencyCallingPolicy [[-Identity] <string>] [-Description <string>] [-EnhancedEmergencyServiceDisclaimer <string>]
 [-ExternalLocationLookupMode <string>] [-NotificationDialOutNumber <string>] [-NotificationGroup <string>] [-NotificationMode <Object>]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
This cmdlet modifies an existing Teams Emergency Calling policy. Emergency calling policy is used for the life cycle of emergency calling experience for the security desk and Teams client location experience.

## EXAMPLES

### Example 1
```powershell
Set-CsTeamsEmergencyCallingPolicy -Identity "testECP" -NotificationGroup "123@gh.com;567@test.com"
```

This example modifies an existing cmdlet with identity testECP.

## PARAMETERS

### -Description
Provides a description of the Teams Emergency Calling policy to identify the purpose of setting it.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EnhancedEmergencyServiceDisclaimer
Allows the tenant administrator to configure a text string, which is shown at the top of the Calls app. The user can acknowledge the string by selecting OK. The string will be shown on client restart.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExternalLocationLookupMode
Enables ExternalLocationLookupMode. This mode allows users to set Emergency addresses for remote locations.

```yaml
Type: String
Parameter Sets: (All)
Aliases:
Accepted values: Disabled, Enabled

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Identity
The Identity parameter is a unique identifier that designates the name of the policy

```yaml
Type: String
Parameter Sets: Identity
Aliases:

Required: False
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -NotificationDialOutNumber
This parameter represents the PSTN number which can be dialed out if NotificationMode is set to either of the two Conference values.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -NotificationGroup
NotificationGroup is a email list of users and groups to be notified of an emergency call. Individual users or groups are separated by ";", for instance "group1@contoso.com;group2@contoso.com". A maximum of 50 users can be notified.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -NotificationMode
The type of conference experience for security desk notification. Support for the ConferenceUnMuted mode is pending.

```yaml
Type: Microsoft.Rtc.Management.WritableConfig.Policy.Teams.NotificationMode
Parameter Sets: (All)
Aliases:
Accepted values: NotificationOnly, ConferenceMuted, ConferenceUnMuted

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (https://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[New-CsTeamsEmergencyCallingPolicy](New-CsTeamsEmergencyCallingPolicy.md)

[Get-CsTeamsEmergencyCallingPolicy](Get-CsTeamsEmergencyCallingPolicy.md)

[Remove-CsTeamsEmergencyCallingPolicy](Remove-CsTeamsEmergencyCallingPolicy.md)

[Grant-CsTeamsEmergencyCallingPolicy](Grant-CsTeamsEmergencyCallingPolicy.md)
