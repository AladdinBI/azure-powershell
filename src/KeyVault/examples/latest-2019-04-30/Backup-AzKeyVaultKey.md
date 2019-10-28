
### Example 1: Sets the certificate contacts for the specified key vault.
```powershell
PS C:\> Add-AzKeyVaultCertificateContact -EmailAddress {EmailAddress} -VaultName {VaultName}



### Example 2: Requests that a backup of the specified certificate be downloaded to the client.
```powershell
PS C:\> Backup-AzKeyVaultCertificate -Name {Name} -OutputFile {OutputFile} -VaultName {VaultName}



### Example 3: The Key Backup operation exports a key from Azure Key Vault in a protected form.
```powershell
PS C:\> Backup-AzKeyVaultKey -DefaultProfile {DefaultProfile} -Force {Force} -Name {Name} -OutputFile {OutputFile} -VaultName {VaultName}


