
### Example 1: Sets the certificate contacts for the specified key vault.
```powershell
PS C:\> Add-AzKeyVaultCertificateContact -EmailAddress {EmailAddress} -VaultName {VaultName}



### Example 1: Requests that a backup of the specified certificate be downloaded to the client.
```powershell
PS C:\> Backup-AzKeyVaultCertificate -Name {Name} -OutputFile {OutputFile} -VaultName {VaultName}


