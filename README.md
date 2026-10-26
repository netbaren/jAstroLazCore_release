# jAstroLaz — visual astronomy for Windows

*[Version française](README.fr.md)*

Windows 64-bit executable package.
<img width="668" height="481" alt="image" src="https://github.com/user-attachments/assets/28e2b745-4eeb-4b90-85a9-6c990599c731" />
Private source commit: 66a2701
Package file: jAstroLaz-win64-2.4.zip
SHA256: e38820edd5e96c25560d96c15ef5c18e84fbb90a8d67950c9a039d41b4a0da01

**jAstroLaz** is free astronomy software for Windows, written in **Lazarus / Free Pascal**.
It is not a sky encyclopedia but rather a **visual astronomy book**: it shows and explains what happens above our heads.

jAstroLaz is a personal astronomy application for Windows, developed with Lazarus / Free Pascal. It brings together calculations, interactive diagrams, animations and explanatory material to help explore and understand what we observe.
Its main focus is the study of time (solar, civil, sidereal…) and the Solar System: the Sun, the Moon, Earth and the planets, their apparent motions and associated phenomena. A planetarium extends this exploration to the starry sky.

## Features
- **Astrolabe**: an animated astrolabe showing how this ancient instrument maps the sky.
- **Sun path with local relief**: the Sun's course drawn over the real mountain skyline of the site, to see when the Sun actually rises behind the ridges.
- **Equation of time**: the difference between solar time and clock time throughout the year.
- **Time travel**: display the sky at any date, past or future.
- **Starry sky**: bright stars, Milky Way, planets.
- Several **observing sites** (Geneva by default, clear horizon).

## Download and install

1. Go to **[Releases](https://github.com/netbaren/jAstroLazCore_release/releases)** and take the latest version.
2. Two formats:
   - `jAstroLaz_v2.4.exe`: installer (built with [Inno Setup](https://jrsoftware.org/isinfo.php), a widely used free installer);
   - `jAstroLaz-win64-2.4.zip`: portable version, unzip and run, no installation.
3. Details: [INSTALLATION_WINDOWS.md](INSTALLATION_WINDOWS.md).

Requirements: Windows 10 or 11, 64-bit.

### "Windows protected your PC"?

jAstroLaz is not signed with a (paid) commercial certificate, so Windows SmartScreen warns about it like any new program it doesn't know yet. Click **More info**, then **Run anyway**.

## Security and verification

| File | SHA-256 | Antivirus scan |
|---|---|---|
| `jAstroLaz_v2.4.exe` | `2cc695ee5e0874406b14f27aa7d11de45a0e0ad35badcf169a496b7b500caa24` | [VirusTotal: 0 / 64 detections](https://www.virustotal.com/gui/file/2cc695ee5e0874406b14f27aa7d11de45a0e0ad35badcf169a496b7b500caa24) |

| `jAstroLaz-win64-2.4.zip` | `e38820edd5e96c25560d96c15ef5c18e84fbb90a8d67950c9a039d41b4a0da01` | [VirusTotal: No security vendors flagged this file as malicious](https://www.virustotal.com/gui/file/e38820edd5e96c25560d96c15ef5c18e84fbb90a8d67950c9a039d41b4a0da01?nocache=1) |

```powershell 
Get-FileHash .\jAstroLaz_v2.4.exe

**The program does not connect to the Internet and collects no data.**

## History
Started around 2004–2007 in **Java** (Eclipse), revived in 2020, and fully rewritten in **Lazarus / Free Pascal** from 2026 with the help of AI assistants (Claude, Codex).

## Credits
- Inspirations: Juergen Giesen's astronomy applets, JPARSEC (T. Alonso Albi), JavAstro (Filippo Bisognano).
- Data and models: Bright Star Catalog, VSOP87, INPOP19a, IANA TZDB / PascalTZ, SkyChart / Cartes du Ciel Milky Way data.
- Details and licences: [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt).

## Contact
René Barnet — rene.barnet [at] proton [dot] me — see [CONTACT.md](CONTACT.md)
