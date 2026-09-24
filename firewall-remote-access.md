# Firewall & Remote Access

| Command | Description |
|---------|-------------|
| `wf.msc` | Open Windows Firewall |
| `netsh advfirewall show allprofiles` | Show firewall profiles |
| `Get-NetFirewallProfile` | Inspect firewall profile state |
| `Get-NetFirewallRule` | List firewall rules |
| `query user` | Show active user sessions |
| `qwinsta` | List RDP sessions |
| `Get-Service TermService` | Check Remote Desktop service |
| `Get-NetTCPConnection -LocalPort 3389` | Check active RDP connections |
| `wuauclt /updatenow` | Start updates |
| `usoclient startscan` | Scan for updates |
| `usoclient startinstall` | Install updates |
| `Get-Command *network*` | Find network commands |
