To verify the last logon date of a single user, use this Powershell line:
Get-ADUser username -Properties LastLogonDate | Select SamAccountName, LastLogonDate
