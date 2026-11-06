# jAstroLaz — astronomie visuelle pour Windows

*[English version below ⇩](#jastrolaz--visual-astronomy-for-windows)*

**jAstroLaz** est un logiciel d'astronomie gratuit pour Windows, écrit en **Lazarus / Free Pascal**.
Ce n'est pas une encyclopédie du ciel : c'est plutôt un **livre d'astronomie visuel**, qui montre et explique ce qui se passe au-dessus de nos têtes.

<img width="668" height="481" alt="Capture d'écran de jAstroLaz, logiciel d'astronomie : astrolabe et ciel" src="https://github.com/user-attachments/assets/28e2b745-4eeb-4b90-85a9-6c990599c731" />

## Ce que fait jAstroLaz

- **Astrolabe** : un astrolabe animé, pour comprendre comment cet instrument ancien représente le ciel.
- **Trajectoire du Soleil** avec le **relief local** : la course du Soleil est tracée au-dessus du profil réel des montagnes de l'horizon (par exemple pour un site en Valais), pour savoir quand le Soleil se lève vraiment derrière les crêtes.
- **Équation du temps** : l'écart entre l'heure solaire et l'heure de la montre, au fil de l'année.
- **Voyage dans le temps** : on peut afficher le ciel à n'importe quelle date, passée ou future, et pas seulement maintenant.
- **Ciel étoilé** : étoiles brillantes, Voie lactée, planètes.
- **Liste de sites d'observation** (Genève par défaut, horizon dégagé).

## Sécurité et vérification

Chaque fichier publié est vérifié par VirusTotal avant mise en ligne. Empreintes SHA-256 et liens des rapports : [VIRUSTOTAL.md](VIRUSTOTAL.md).

## Téléchargement et installation

1. Ouvrir la page **[Releases](https://github.com/netbaren/jAstroLazCore_release/releases)** et prendre la dernière version.
2. Deux formats au choix :
   - `jAstroLaz_v2.4.7.exe` : installeur (réalisé avec [Inno Setup](https://jrsoftware.org/isinfo.php), un installeur gratuit très répandu) ;
   - `jAstroLaz-win64-2.4.7.zip` : version portable, à décompresser et lancer sans installation.
3. Détails : voir [INSTALLATION_WINDOWS_FR.md](INSTALLATION_WINDOWS_FR.md).

Configuration : Windows 10 ou 11, 64 bits.

### Message « Windows a protégé votre ordinateur » ?

jAstroLaz n'est pas signé avec un certificat commercial (payant). Windows SmartScreen affiche donc un avertissement pour tout programme récent qu'il ne connaît pas encore. Cliquer sur **Informations complémentaires**, puis **Exécuter quand même**.

Le programme ne se connecte à Internet que pour la vérification manuelle des mises à jour (menu dédié, qui interroge uniquement les releases publiques sur GitHub, sans envoyer ni collecter la moindre donnée).
Aucune autre fonction n'accède au réseau.

## Un peu d'histoire

Le projet est né vers 2004–2007 en **Java**, sous Eclipse, à partir d'une passion pour les calculs astronomiques.
Repris en 2020, il a été entièrement réécrit en **Lazarus / Free Pascal** à partir de 2026, avec l'aide d'assistants IA (Claude, Codex).

## Remerciements et sources

- Inspirations : applets d'astronomie de Juergen Giesen, JPARSEC (T. Alonso Albi), JavAstro (Filippo Bisognano).
- Gnomonique : [Shadows Pro](https://www.shadowspro.com) (François Blateyron), référence pour le cadran solaire et l'astrolabe.
- Données et modèles : Bright Star Catalog, VSOP87 et INPOP19a (Observatoire de Paris, Licence Ouverte 2.0), IANA TZDB / PascalTZ, données Voie lactée de SkyChart / Cartes du Ciel, tracés des constellations dérivés de JPARSEC.
- Détails et licences : [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt).

## Licence

Logiciel gratuit, pour une utilisation non commerciale uniquement, distribué sous forme compilée.
Les autorisations et mentions des tiers (Observatoire de Paris / ex-IMCCE, JPARSEC, Shadows Pro) sont détaillées dans [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt).

## Contact

René Barnet — rene.barnet [at] proton [dot] me — voir [CONTACT.md](CONTACT.md)

---

# jAstroLaz — visual astronomy for Windows

*[⇧ Version française](#jastrolaz--astronomie-visuelle-pour-windows)*

**jAstroLaz** is a free astronomy application for Windows, written in **Lazarus / Free Pascal**.
It isn't an encyclopedia of the sky: think of it more as a **visual astronomy book**, showing and explaining what's happening above our heads.

<img width="668" height="481" alt="Screenshot of jAstroLaz, astronomy software: astrolabe and sky" src="https://github.com/user-attachments/assets/28e2b745-4eeb-4b90-85a9-6c990599c731" />

## What jAstroLaz does

- **Astrolabe**: an animated astrolabe, to understand how this ancient instrument represents the sky.
- **Sun's path** with **local relief**: the Sun's course is plotted against the real profile of the surrounding mountains (for example for a site in the Valais), so you can tell when the Sun actually rises from behind the ridgeline.
- **Equation of time**: the gap between solar time and clock time, through the year.
- **Time travel**: the sky can be displayed for any date, past or future, not just now.
- **Starry sky**: bright stars, the Milky Way, planets.
- **List of observation sites** (Geneva by default, clear horizon).

## Security and verification

Each published file is scanned by VirusTotal before release. SHA-256 fingerprints and report links: [VIRUSTOTAL_EN.md](VIRUSTOTAL_EN.md).

## Download and installation

1. Open the **[Releases](https://github.com/netbaren/jAstroLazCore_release/releases)** page and grab the latest version.
2. Two formats available:
   - `jAstroLaz_v2.4.7.exe`: installer (built with [Inno Setup](https://jrsoftware.org/isinfo.php), a widely used free installer);
   - `jAstroLaz-win64-2.4.7.zip`: portable version, just unzip and run, no installation needed.
3. Details: see [INSTALLATION_WINDOWS.md](INSTALLATION_WINDOWS.md).

Requirements: Windows 10 or 11, 64-bit.

### "Windows protected your PC" message?

jAstroLaz isn't signed with a commercial (paid) certificate. Windows SmartScreen shows this warning for any recent program it doesn't yet recognize. Click **More info**, then **Run anyway**.

The program only connects to the Internet for the manual update check (dedicated menu, which only queries the public releases on GitHub, without sending or collecting any data).
No other feature accesses the network.

## A bit of history

The project was born around 2004–2007 in **Java**, under Eclipse, out of a passion for astronomical calculations.
Picked back up in 2020, it was entirely rewritten in **Lazarus / Free Pascal** starting in 2026, with the help of AI assistants (Claude, Codex).

## Acknowledgements and sources

- Inspirations: astronomy applets by Juergen Giesen, JPARSEC (T. Alonso Albi), JavAstro (Filippo Bisognano).
- Gnomonics: [Shadows Pro](https://www.shadowspro.com) (François Blateyron), reference for the sundial and astrolabe.
- Data and models: Bright Star Catalog, VSOP87 and INPOP19a (Paris Observatory, Licence Ouverte 2.0 / Open Licence), IANA TZDB / PascalTZ, Milky Way data from SkyChart / Cartes du Ciel, constellation figures derived from JPARSEC.
- Details and licenses: [THIRD_PARTY_NOTICES_EN.txt](THIRD_PARTY_NOTICES_EN.txt).

## License

Free software, for non-commercial use only, distributed in compiled form.
Third-party permissions and credits (Paris Observatory / formerly IMCCE, JPARSEC, Shadows Pro) are detailed in [THIRD_PARTY_NOTICES_EN.txt](THIRD_PARTY_NOTICES_EN.txt).

## Contact

René Barnet — rene.barnet [at] proton [dot] me — see [CONTACT.md](CONTACT.md)
