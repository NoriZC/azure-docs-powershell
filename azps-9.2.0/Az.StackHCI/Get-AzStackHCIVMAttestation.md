---
external help file: 
Module Name: Az.StackHCI
online version: https://learn.microsoft.com/powershell/module/az.stackhci/get-azstackhcivmattestation
schema: 2.0.0
content_git_url: https://github.com/Azure/azure-powershell/blob/main/src/StackHCI/help/Get-AzStackHCIVMAttestation.md
original_content_git_url: https://github.com/Azure/azure-powershell/blob/main/src/StackHCI/help/Get-AzStackHCIVMAttestation.md
---

# Get-AzStackHCIVMAttestation

## SYNOPSIS
Get-AzStackHCIVMAttestation shows a list of guests added to IMDS Attestation on a node.

> [!NOTE]
>This is the previous version of our documentation. Please consult [the most recent version](/powershell/module/az.stackhci/get-azstackhcivmattestation) for up-to-date information.

## SYNTAX

```
Get-AzStackHCIVMAttestation [-Local] [<CommonParameters>]
```

## DESCRIPTION
Get-AzStackHCIVMAttestation shows a list of guests added to IMDS Attestation on a node.

## EXAMPLES

### Example 1: 
```powershell
Get-AzStackHCIVMAttestation
```

```output
Name        AttestationHost    Status
----        ---------------    ------
183hcinode1 HCINODE2        Connected
bhat2       HCINODE2        Connected
ppnt3n1     HCINODE2        Connected
ppt3n0      HCINODE2        Connected
ppt5pn0     HCINODE2        Connected
ppt6pn0     HCINODE2        Connected
ppt7pn0     HCINODE2        Connected
```

Get all guests with IMDS Attestation on cluster.

### Example 2: 
```powershell
Get-AzStackHCIVMAttestation -Local
```

```output
Name        AttestationHost    Status
----        ---------------    ------
183hcinode1 HCINODE2        Connected
bhat2       HCINODE2        Connected
ppnt3n1     HCINODE2        Connected
ppt3n0      HCINODE2        Connected
ppt5pn0     HCINODE2        Connected
ppt6pn0     HCINODE2        Connected
ppt7pn0     HCINODE2        Connected
```

Gets guests with Attestation from the node executing the cmdlet.

## PARAMETERS

### -Local
Only retrieve guests with Attestation from the node executing the cmdlet.

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

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### System.Management.Automation.PSObject

## NOTES

ALIASES

## RELATED LINKS

