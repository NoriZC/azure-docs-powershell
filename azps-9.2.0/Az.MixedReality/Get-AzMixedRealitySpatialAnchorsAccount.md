---
external help file: 
Module Name: Az.MixedReality
online version: https://docs.microsoft.com/powershell/module/az.mixedreality/get-azmixedrealityspatialanchorsaccount
schema: 2.0.0
content_git_url: https://github.com/Azure/azure-powershell/blob/main/src/MixedReality/help/Get-AzMixedRealitySpatialAnchorsAccount.md
original_content_git_url: https://github.com/Azure/azure-powershell/blob/main/src/MixedReality/help/Get-AzMixedRealitySpatialAnchorsAccount.md
---

# Get-AzMixedRealitySpatialAnchorsAccount

## SYNOPSIS
Retrieve a Spatial Anchors Account.

> [!NOTE]
>This is the previous version of our documentation. Please consult [the most recent version](/powershell/module/az.mixedreality/get-azmixedrealityspatialanchorsaccount) for up-to-date information.

## SYNTAX

### List (Default)
```
Get-AzMixedRealitySpatialAnchorsAccount [-SubscriptionId <String[]>] [-DefaultProfile <PSObject>]
 [<CommonParameters>]
```

### Get
```
Get-AzMixedRealitySpatialAnchorsAccount -Name <String> -ResourceGroupName <String>
 [-SubscriptionId <String[]>] [-DefaultProfile <PSObject>] [<CommonParameters>]
```

### GetViaIdentity
```
Get-AzMixedRealitySpatialAnchorsAccount -InputObject <IMixedRealityIdentity> [-DefaultProfile <PSObject>]
 [<CommonParameters>]
```

### List1
```
Get-AzMixedRealitySpatialAnchorsAccount -ResourceGroupName <String> [-SubscriptionId <String[]>]
 [-DefaultProfile <PSObject>] [<CommonParameters>]
```

## DESCRIPTION
Retrieve a Spatial Anchors Account.

## EXAMPLES

### Example 1: List Spatial Anchors Accounts by Subscription.
```powershell
Get-AzMixedRealitySpatialAnchorsAccount
```

```output
Location Name                   ResourceGroupName
-------- ----                   -----------------
eastus   azpstestanchorsaccount azps_test_group
```

List Spatial Anchors Accounts by Subscription.

### Example 2: List Spatial Anchors Accounts by Resource Group.
```powershell
Get-AzMixedRealitySpatialAnchorsAccount -ResourceGroupName azps_test_group
```

```output
Location Name                   ResourceGroupName
-------- ----                   -----------------
eastus   azpstestanchorsaccount azps_test_group
```

List Spatial Anchors Accounts by Resource Group.

### Example 3: Retrieve a Spatial Anchors Account.
```powershell
Get-AzMixedRealitySpatialAnchorsAccount -Name azpstestanchorsaccount -ResourceGroupName azps_test_group
```

```output
Location Name                   ResourceGroupName
-------- ----                   -----------------
eastus   azpstestanchorsaccount azps_test_group
```

Retrieve a Spatial Anchors Account.

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

### -InputObject
Identity Parameter
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.MixedReality.Models.IMixedRealityIdentity
Parameter Sets: GetViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Name
Name of an Mixed Reality Account.

```yaml
Type: System.String
Parameter Sets: Get
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ResourceGroupName
Name of an Azure resource group.

```yaml
Type: System.String
Parameter Sets: Get, List1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SubscriptionId
The Azure subscription ID.
This is a GUID-formatted string (e.g.
00000000-0000-0000-0000-000000000000)

```yaml
Type: System.String[]
Parameter Sets: Get, List, List1
Aliases:

Required: False
Position: Named
Default value: (Get-AzContext).Subscription.Id
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Azure.PowerShell.Cmdlets.MixedReality.Models.IMixedRealityIdentity

## OUTPUTS

### Microsoft.Azure.PowerShell.Cmdlets.MixedReality.Models.Api20210301Preview.ISpatialAnchorsAccount

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`INPUTOBJECT <IMixedRealityIdentity>`: Identity Parameter
  - `[AccountName <String>]`: Name of an Mixed Reality Account.
  - `[Id <String>]`: Resource identity path
  - `[Location <String>]`: The location in which uniqueness will be verified.
  - `[ResourceGroupName <String>]`: Name of an Azure resource group.
  - `[SubscriptionId <String>]`: The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

## RELATED LINKS

