# Check Windows License
(Get-WmiObject -query 'select * from SoftwareLicensingService').OA3xOriginalProductKey

# Check Startup Application
Get-CimInstance Win32_StartupCommand | Select-Object Name, Command, Location | Format-Table -AutoSize
