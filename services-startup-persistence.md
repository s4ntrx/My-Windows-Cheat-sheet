# Services, Startup & Persistence Checks

| Command | Description |
|---------|-------------|
| `sc query` | List running services |
| `sc qc WinDefend` | Show Defender service configuration |
| `Get-Service \| Where-Object {$_.Status -eq 'Running'}` | Display running services |
| `Get-CimInstance Win32_StartupCommand` | Show startup commands |
| `reg query "HKLM\Software\Microsoft\Windows\CurrentVersion\Run"` | Check machine-level startup entries |
| `reg query "HKCU\Software\Microsoft\Windows\CurrentVersion\Run"` | Check user-level startup entries |
| `wmic startup list full` | List startup programs |
| `Restart-Computer -Force` | Force restart computer |
