# Vérification VirusTotal

*[English version](VIRUSTOTAL_EN.md)*

État de la version actuellement publiée. Pour l'historique des versions précédentes, voir les notes de chaque [Release](https://github.com/netbaren/jAstroLazCore_release/releases) (chaque release garde son propre rapport).

Private source commit: 7aaf944

Chaque fichier publié a été vérifié par VirusTotal, comme en témoignent les comptes rendus ci-dessous :

|     Fichier                 |   SHA-256                                                          | Analyse antivirus                                                                                                                      |
|------------------------------|---------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| `jAstroLaz_v2.4.7.exe`      | `51efe332243d9a90fc9d31b8d509d403e3629ce51772ad59b5f8326c2b0532ba` | [VirusTotal : 0/65 détections](https://www.virustotal.com/gui/file/51efe332243d9a90fc9d31b8d509d403e3629ce51772ad59b5f8326c2b0532ba) |
| `jAstroLaz-win64-2.4.7.zip` | `2d86e1969faf966251a19c2a75c8e6f8a210c46a024a73902e08a149196b2bdc` | [VirusTotal : 0/59 détections](https://www.virustotal.com/gui/file/2d86e1969faf966251a19c2a75c8e6f8a210c46a024a73902e08a149196b2bdc) |

Pour vérifier les empreintes sous PowerShell :

```powershell
cd [dossier d'implantation]
Get-FileHash .\jAstroLaz_v2.4.7.exe, .\jAstroLaz-win64-2.4.7.zip
```
