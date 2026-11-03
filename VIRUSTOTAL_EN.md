# VirusTotal verification

*[Version française](VIRUSTOTAL.md)*

Status of the currently published version. For the history of previous versions, see the notes of each [Release](https://github.com/netbaren/jAstroLazCore_release/releases) (each release keeps its own report).

Private source commit: 7aaf944

Each published file has been scanned by VirusTotal, as shown in the reports below:

|     File                    |   SHA-256                                                          | Antivirus scan                                                                                                                      |
|------------------------------|---------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| `jAstroLaz_v2.4.7.exe`      | `51efe332243d9a90fc9d31b8d509d403e3629ce51772ad59b5f8326c2b0532ba` | [VirusTotal: 0/65 detections](https://www.virustotal.com/gui/file/51efe332243d9a90fc9d31b8d509d403e3629ce51772ad59b5f8326c2b0532ba) |
| `jAstroLaz-win64-2.4.7.zip` | `2d86e1969faf966251a19c2a75c8e6f8a210c46a024a73902e08a149196b2bdc` | [VirusTotal: 0/59 detections](https://www.virustotal.com/gui/file/2d86e1969faf966251a19c2a75c8e6f8a210c46a024a73902e08a149196b2bdc) |

To check the fingerprints in PowerShell:

```powershell
cd [installation folder]
Get-FileHash .\jAstroLaz_v2.4.7.exe, .\jAstroLaz-win64-2.4.7.zip
```
