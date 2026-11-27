## ✅ Check Windows License
(Get-WmiObject -query 'select * from SoftwareLicensingService').OA3xOriginalProductKey

## ✅ Check Startup Applications
Get-CimInstance Win32_StartupCommand | Select-Object Name, Command, Location | Format-Table -AutoSize
