---
external help file: Az.EventHub-help.xml
Module Name: Az.EventHub
online version: https://learn.microsoft.com/powershell/module/az.EventHub/new-AzEventHubKeyVaultPropertiesObject
schema: 2.0.0
content_git_url: https://github.com/Azure/azure-powershell/blob/main/src/EventHub/EventHub/help/New-AzEventHubKeyVaultPropertiesObject.md
original_content_git_url: https://github.com/Azure/azure-powershell/blob/main/src/EventHub/EventHub/help/New-AzEventHubKeyVaultPropertiesObject.md
---

# New-AzEventHubKeyVaultPropertiesObject

## SYNOPSIS
Create an in-memory object for KeyVaultProperties.

> [!NOTE]
>This is the previous version of our documentation. Please consult [the most recent version](/powershell/module/az.eventhub/new-azeventhubkeyvaultpropertiesobject) for up-to-date information.

## SYNTAX

```
New-AzEventHubKeyVaultPropertiesObject [-KeyName <String>] [-KeyVaultUri <String>] [-KeyVersion <String>]
 [-UserAssignedIdentity <String>] [<CommonParameters>]
```

## DESCRIPTION
Create an in-memory object for KeyVaultProperties.

## EXAMPLES

### Example 1: Construct an in-memory KeyVaultProperties object
```powershell
New-AzEventHubKeyVaultPropertiesObject -KeyName key1 -KeyVaultUri https://testkeyvault.vault.azure.net
```

Creates an in-memory object of type `IKeyVaultProperties`.
An array of `IKeyVaultProperties` can be fed as 
input to `KeyVaultProperty` parameter of New-AzEventHubNamespaceV2 and Set-AzEventHubNamespaceV2 to enable encryption.

## PARAMETERS

### -KeyName
Name of the Key from KeyVault.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -KeyVaultUri
Uri of KeyVault.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -KeyVersion
Key Version.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserAssignedIdentity
ARM ID of user Identity selected for encryption.

```yaml
Type: System.String
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

### Microsoft.Azure.PowerShell.Cmdlets.EventHub.Models.Api202201Preview.KeyVaultProperties

## NOTES

ALIASES

## RELATED LINKS
