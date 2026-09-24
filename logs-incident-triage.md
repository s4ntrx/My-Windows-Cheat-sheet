# Logs & Incident Triage

| Command | Description |
|---------|-------------|
| `wevtutil qe Security /c:20 /f:text` | Show the latest 20 Security log events |
| `Get-WinEvent -LogName Security -MaxEvents 20` | Display recent security events |
| `Get-WinEvent -FilterHashtable @{LogName='System'; ID=7045} -MaxEvents 10` | Show recent service installation events |
| `Get-WinEvent -FilterHashtable @{LogName='Security'; ID=4625} -MaxEvents 20` | Show failed logon attempts |
| `schtasks /query /fo LIST /v` | List scheduled tasks in detail |
| `Get-ScheduledTask` | Enumerate scheduled tasks in PowerShell |
| `tasklist /svc` | Show running processes with services |
| `Get-Process \| Sort CPU -Descending \| Select -First 10` | Display top CPU-consuming processes |
