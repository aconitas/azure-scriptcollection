# Description
This Script creates a service principal called 'Parallels RAS' for the RAS AVD connection. 

Information source: https://kb.parallels.com/125236

# Parameter
| Parameter | Default Value | Description |
|---|---|---|
| TenantId | n/a | n/a |
| SubscriptionID | n/a | n/a |
| ResourceGroups | n/a | n/a |


# Usage Example
```powershell

PS C:\Temp\Create-SP-ParallelsAVD.ps1 -TenantID 00000000-0000-0000-0000-000000000000 -SubscriptionID 00000000-0000-0000-0000-000000000000 -ResourceGroups 'test-rg','test2-rg'
```