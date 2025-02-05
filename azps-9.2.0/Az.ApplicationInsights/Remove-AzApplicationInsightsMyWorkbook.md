---
external help file: 
Module Name: Az.ApplicationInsights
online version: https://learn.microsoft.com/powershell/module/az.applicationinsights/remove-azapplicationinsightsmyworkbook
schema: 2.0.0
content_git_url: https://github.com/Azure/azure-powershell/blob/main/src/ApplicationInsights/help/Remove-AzApplicationInsightsMyWorkbook.md
original_content_git_url: https://github.com/Azure/azure-powershell/blob/main/src/ApplicationInsights/help/Remove-AzApplicationInsightsMyWorkbook.md
---

# Remove-AzApplicationInsightsMyWorkbook

## SYNOPSIS
Delete a private workbook.

> [!NOTE]
>This is the previous version of our documentation. Please consult [the most recent version](/powershell/module/az.applicationinsights/remove-azapplicationinsightsmyworkbook) for up-to-date information.

## SYNTAX

```
Remove-AzApplicationInsightsMyWorkbook -Name <String> -ResourceGroupName <String> [-SubscriptionId <String>]
 [-DefaultProfile <PSObject>] [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Delete a private workbook.

## EXAMPLES

### Example 1: Delete a private workbook
```powershell
Remove-AzApplicationInsightsMyWorkbook -ResourceGroupName appinsights-hkrs2v-test -Name c65b3461-9270-45b7-b6ad-ddd644458b0eR
```

Delete a private workbook.

## PARAMETERS

### -DefaultProfile
The credentials, account, tenant, and subscription used for communication with Azure.

```yaml
Type: System.Management.Automation.PSObject
Parameter Sets: (All)
Aliases: AzureRMContext, AzureCredential

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
The name of the Application Insights component resource.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PassThru
Returns true when the command succeeds

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ResourceGroupName
The name of the resource group.
The name is case insensitive.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SubscriptionId
The ID of the target subscription.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: (Get-AzContext).Subscription.Id
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: cf

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
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

## RELATED LINKS

