# jAstroLaz — astronomie visuelle pour Windows

*[English version](README_us_EN.md)*

**jAstroLaz** est un logiciel d'astronomie gratuit pour Windows, écrit en **Lazarus / Free Pascal**.
Ce n'est pas une encyclopédie du ciel : c'est plutôt un **livre d'astronomie visuel**, qui montre et explique ce qui se passe au-dessus de nos têtes.

<img width="668" height="481" alt="image" src="https://github.com/user-attachments/assets/28e2b745-4eeb-4b90-85a9-6c990599c731" />

## Ce que fait jAstroLaz

- **Astrolabe** : un astrolabe animé, pour comprendre comment cet instrument ancien représente le ciel.
- **Trajectoire du Soleil** avec le **relief local** : la course du Soleil est tracée au-dessus du profil réel des montagnes de l'horizon (par exemple pour un site en Valais), pour savoir quand le Soleil se lève vraiment derrière les crêtes.
- **Équation du temps** : l'écart entre l'heure solaire et l'heure de la montre, au fil de l'année.
- **Voyage dans le temps** : on peut afficher le ciel à n'importe quelle date, passée ou future, et pas seulement maintenant.
- **Ciel étoilé** : étoiles brillantes, Voie lactée, planètes.
- **Liste de sites d'observation** (Genève par défaut, horizon dégagé).

## Sécurité et vérification

Private source commit: f3ea157

Chaque fichier publié a été vérifié par VirusTotal comme en témoignent les compte rendus ci-dessous :

|     Fichier               |   SHA-256                                                          | Analyse antivirus                                                                                                                      |
|---------------------------|--------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| `jAstroLaz_v2.4.exe`      | `1a4bf3fe6cc2b06f906c054bde0a3946ef729e63f122075f26f8ecdf31468866` | [VirusTotal : 0 / 64 détection](https://www.virustotal.com/gui/file/1a4bf3fe6cc2b06f906c054bde0a3946ef729e63f122075f26f8ecdf31468866 ) |
| `jAstroLaz-win64-2.4.zip` | `a53c69ded77876ce838415b809812f53cb37f9e6b5d1ec426800bf19c684f712` | [VirusTotal : 0 / 66 détection](https://www.virustotal.com/gui/file/a53c69ded77876ce838415b809812f53cb37f9e6b5d1ec426800bf19c684f712 ) |

Pour vérifier les empreintes sous PowerShell :

```powershell
cd [dossier d'implantation]
Get-FileHash .\jAstroLaz_v2.4.exe, .\jAstroLaz-win64-2.4.zip
```

## Téléchargement et installation

1. Ouvrir la page **[Releases](https://github.com/netbaren/jAstroLazCore_release/releases)** et prendre la dernière version.
2. Deux formats au choix :
   - `jAstroLaz_v2.4.exe` : installeur (réalisé avec [Inno Setup](https://jrsoftware.org/isinfo.php), un installeur gratuit très répandu) ;
   - `jAstroLaz-win64-2.4.zip` : version portable, à décompresser et lancer sans installation.
3. Détails : voir [INSTALLATION_WINDOWS_FR.md](INSTALLATION_WINDOWS_FR.md).

Configuration : Windows 10 ou 11, 64 bits.

### Message « Windows a protégé votre ordinateur » ?

jAstroLaz n'est pas signé avec un certificat commercial (payant). Windows SmartScreen affiche donc un avertissement pour tout programme récent qu'il ne connaît pas encore. Cliquer sur **Informations complémentaires**, puis **Exécuter quand même**.
Le programme ne se connecte à Internet que pour la vérification manuelle des mises à jour (menu dédié, interroge uniquement les releases publiques sur GitHub, sans envoyer ni collecter la moindre donnée). 
Aucune autre fonction n’accède au réseau.

## Un peu d'histoire

Le projet est né vers 2004–2007 en **Java**, sous Eclipse, à partir d'une passion pour les calculs astronomiques.
Repris en 2020, il a été entièrement réécrit en **Lazarus / Free Pascal** à partir de 2026, avec l'aide d'assistants IA (Claude, Codex).

## Remerciements et sources

- Inspirations : applets d'astronomie de Juergen Giesen, JPARSEC (T. Alonso Albi), JavAstro (Filippo Bisognano).
- Données et modèles : Bright Star Catalog, VSOP87, INPOP19a, IANA TZDB / PascalTZ, données Voie lactée de SkyChart / Cartes du Ciel.
- Détails et licences : [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt).

## Licence

Logiciel gratuit (pour Utilisation Non commerciale seulement), distribué sous forme compilée. 
(publication des droits IMCC, JPARSEC, SHADOWS à venir prochainement)

## Contact

René Barnet — rene.barnet [at] proton [dot] me — voir [CONTACT.md](CONTACT.md)
