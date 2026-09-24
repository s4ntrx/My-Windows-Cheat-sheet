# Defender & Threat Protection

| Command | Description |
|---------|-------------|
| `Get-MpComputerStatus` | Display Defender health and status |
| `Update-MpSignature` | Update Microsoft Defender signatures |
| `Start-MpScan -ScanType QuickScan` | Run a quick malware scan |
| `Start-MpScan -ScanType FullScan` | Run a full malware scan |
| `Get-MpThreat` | List detected threats |
| `Get-MpThreatDetection` | Show threat detection history |
| `Get-MpPreference` | Display Defender configuration |
| `netsh advfirewall set allprofiles state on` | Enable firewall |
| `netsh advfirewall show allprofiles` | Show firewall profiles |
| `netsh advfirewall set allprofiles state off` | Disable firewall |
| `Get-ChildItem Env:` | Show environment variables |
