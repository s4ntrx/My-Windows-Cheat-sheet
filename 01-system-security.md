# System Security

| Command | Description |
|---------|-------------|
| `systeminfo` | Display full system information |
| `hostname` | Show device name |
| `whoami /all` | Show current user, groups, and privileges |
| `Get-ComputerInfo` | Display detailed system information |
| `Get-CimInstance Win32_OperatingSystem` | Show Windows OS details |
| `Get-HotFix` | List installed updates and patches |
| `Get-MpComputerStatus` | Check Microsoft Defender status |
| `auditpol /get /category:*` | Display current audit policy settings |
| `sfc /scannow` | Scan and repair system files |
| `DISM /Online /Cleanup-Image /RestoreHealth` | Repair Windows image |
| `netsh wlan delete profile name=profile` | Delete WiFi profile |
| `netsh wlan export profile key=clear` | Export WiFi keys |
| `netsh interface show interface` | Show network interfaces |
