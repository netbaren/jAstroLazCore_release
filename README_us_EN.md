# jAstroLaz — visual astronomy for Windows

*[Version française](README_fr.md)*

**jAstroLaz** is a free astronomy application for Windows, written in **Lazarus / Free Pascal**.
It isn't an encyclopedia of the sky: think of it more as a **visual astronomy book**, showing and explaining what's happening above our heads.

<img width="668" height="481" alt="image" src="https://github.com/user-attachments/assets/28e2b745-4eeb-4b90-85a9-6c990599c731" />

## What jAstroLaz does

- **Astrolabe**: an animated astrolabe, to understand how this ancient instrument represents the sky.
- **Sun's path** with **local relief**: the Sun's course is plotted against the real profile of the surrounding mountains (for example for a site in the Valais), so you can tell when the Sun actually rises from behind the ridgeline.
- **Equation of time**: the gap between solar time and clock time, through the year.
- **Time travel**: the sky can be displayed for any date, past or future, not just now.
- **Starry sky**: bright stars, the Milky Way, planets.
- **List of observation sites** (Geneva by default, clear horizon).

<!-- Add / remove points depending on version 2.4 -->

## Download and installation

1. Open the **[Releases](https://github.com/netbaren/jAstroLazCore_release/releases)** page and grab the latest version.
2. Two formats available:
   - `jAstroLaz_v2.4.exe`: installer (built with [Inno Setup](https://jrsoftware.org/isinfo.php), a widely used free installer) ;
   - `jAstroLaz-win64-2.4.zip`: portable version, just unzip and run, no installation needed.
3. Details: see [INSTALLATION_WINDOWS_EN.md](INSTALLATION_WINDOWS_EN.md).

Requirements: Windows 10 or 11, 64-bit.

### "Windows protected your PC" message?

jAstroLaz isn't signed with a commercial (paid) certificate. Windows SmartScreen shows this warning for any recent program it doesn't yet recognize. Click **More info**, then **Run anyway**.

## Security and verification

Every published file can be verified:

| File | SHA-256 | Antivirus scan |
|------|---------|-----------------|
| `jAstroLaz_v2.4.exe` | `47a3a58f27c73cbff76ee1b8a6afc279ba60cc281a5461ac9aa907303017fce3` | [VirusTotal: 0 / 64 detections](https://www.virustotal.com/gui/file/47a3a58f27c73cbff76ee1b8a6afc279ba60cc281a5461ac9aa907303017fce3) |
| `jAstroLaz-win64-2.4.zip` | `d2c1313e0770337522b6822f6e124a13d74822daafd627654e2547e9c6dc6e4b` | [VirusTotal: 0 / 64 detections](https://www.virustotal.com/gui/file/d2c1313e0770337522b6822f6e124a13d74822daafd627654e2547e9c6dc6e4b) |

To check the fingerprint in PowerShell:

```powershell
Get-FileHash .\jAstroLaz_v2.4.exe
```
The program only connects to the Internet for the manual update check (dedicated menu, which only queries the public releases on GitHub, without sending or collecting any data).
No other feature accesses the network.

## A bit of history

The project was born around 2004–2007 in **Java**, under Eclipse, out of a passion for astronomical calculations.
Picked back up in 2020, it was entirely rewritten in **Lazarus / Free Pascal** starting in 2026, with the help of AI assistants (Claude, Codex).

## Acknowledgements and sources

- Inspirations: astronomy applets by Juergen Giesen, JPARSEC (T. Alonso Albi), JavAstro (Filippo Bisognano).
- Data and models: Bright Star Catalog, VSOP87, INPOP19a, IANA TZDB / PascalTZ, Milky Way data from SkyChart / Cartes du Ciel.
- Details and licenses: [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt).

## License

Free software (for non-commercial use only), distributed in compiled form only.
(publication of IMCC, JPARSEC, and SHADOWS rights to follow shortly)

## Contact

René Barnet — rene.barnet [at] proton [dot] me — see [CONTACT.md](CONTACT.md)