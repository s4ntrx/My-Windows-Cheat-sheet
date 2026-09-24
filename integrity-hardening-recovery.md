# Integrity, Hardening & Recovery

| Command | Description |
|---------|-------------|
| `sfc /scannow` | Scan and repair system files |
| `DISM /Online /Cleanup-Image /RestoreHealth` | Repair Windows image health |
| `chkdsk C: /scan` | Scan disk integrity |
| `gpupdate /force` | Refresh Group Policy settings |
| `secedit /export /cfg C:\security-policy.cfg` | Export local security policy |
| `auditpol /get /category:*` | Review auditing configuration |
| `bcdedit /enum` | Display boot configuration |
| `reagentc /info` | Show Windows recovery environment status |
| `Disable-LocalUser -Name Guest` | Disable Guest account |
| `Get-ComputerInfo` | Misc & Utilities |
| `Enable-LocalUser -Name Administrator` | Enable Administrator |
