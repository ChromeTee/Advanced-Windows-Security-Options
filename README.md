# Advanced-Windows-Security-Options

## Advanced Security Options for Windows: 

### the default domain policy at the following location contains advanced security options:
– ‘Computer Configuration’ > Policies > ‘Windows Settings’ > ‘Security Settings’ > ‘Local Policies’ > ‘Security Options’

### Accounts: Administrator account status
– configuring this policy to disabled will prevent users from being able to log in as the Administrator account (RID 500)

### Accounts: Guest account status
– configuring this policy to disabled will prevent the Guest account from being utilized

 ### Accounts: Rename administrator account
– configuring this policy to change the name of the Administrator account (RID 500), making it more difficult for attackers to utilize.

### Network Security: Force logoff when logon hours expire
– Setting this policy to enabled will automatically log a user off when they reach the end of their authorized logon hours.

### User Account Control: Only elevate executables that are  signed and validated
– configuring this policy will to enable will prevent unsigned binaries from being able to elevate to Administrator level privileges.


"Other policies should be enabled as applicable. If unsure what a particular policy does, open it, and select the ‘Explain’ tab to view a detailed description of the policy, as well as potential issues it may cause" 
