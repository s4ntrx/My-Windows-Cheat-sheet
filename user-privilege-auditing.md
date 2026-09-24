# User & Privilege Auditing

| Command | Description |
|---------|-------------|
| `net user` | List local user accounts |
| `net user username` | Show detailed account information |
| `net localgroup administrators` | List local administrators |
| `whoami /priv` | Show current user privileges |
| `whoami /groups` | Display group memberships |
| `quser` | List logged-in users |
| `Get-LocalUser` | Show local users in PowerShell |
| `Get-LocalGroupMember -Group "Administrators"` | Display members of the Administrators group |
| `net user administrator /active:yes` | Enable admin |
| `del /f /s /q C:\Windows\Temp\*.*` | Delete temp files |
| `rmdir /s /q foldername` | Delete folder |
| `attrib -h -r -s /s /d *.*` | Remove hidden attributes |
