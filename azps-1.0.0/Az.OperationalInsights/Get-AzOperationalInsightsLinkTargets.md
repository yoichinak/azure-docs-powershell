---
external help file: Microsoft.Azure.PowerShell.Cmdlets.OperationalInsights.dll-Help.xml
Module Name: Az.OperationalInsights
ms.assetid: 35C6E85B-E5E1-44E8-86E8-F18E197F69DC
online version: https://docs.microsoft.com/en-us/powershell/module/az.operationalinsights/get-azoperationalinsightslinktargets
schema: 2.0.0
content_git_url: https://github.com/Azure/azure-powershell/blob/master/src/ResourceManager/OperationalInsights/Commands.OperationalInsights/help/Get-AzOperationalInsightsLinkTargets.md
original_content_git_url: https://github.com/Azure/azure-powershell/blob/master/src/ResourceManager/OperationalInsights/Commands.OperationalInsights/help/Get-AzOperationalInsightsLinkTargets.md
---

# Get-AzOperationalInsightsLinkTargets

## SYNOPSIS
Gets accounts that are not associated with a subscription.

## SYNTAX

```
Get-AzOperationalInsightsLinkTargets [-DefaultProfile <IAzureContextContainer>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzOperationalInsightsLinkTargets** cmdlet lists existing accounts that are not associated with an Azure subscription.
To link a new workspace to an existing account, use a customer ID returned by this operation in the customer ID property of a new workspace.

## EXAMPLES

### Example 1: Get unlinked accounts
```
PS C:\>Get-AzOperationalInsightsLinkTargets
```

This command gets unlinked accounts that are owned by the caller's ID.

## PARAMETERS

### -DefaultProfile
The credentials, account, tenant, and subscription used for communication with azure

```yaml
Type: Microsoft.Azure.Commands.Common.Authentication.Abstractions.Core.IAzureContextContainer
Parameter Sets: (All)
Aliases: AzContext, AzureRmContext, AzureCredential

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None

## OUTPUTS

### Microsoft.Azure.Commands.OperationalInsights.Models.PSAccount

## NOTES

## RELATED LINKS

[Azure Operational Insights Cmdlets](./Az.OperationalInsights.md)


