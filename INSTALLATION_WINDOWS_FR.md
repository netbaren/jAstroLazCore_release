# Installer jAstroLazCore sous Windows

Cette page explique comment telecharger, installer et lancer jAstroLazCore sous
Windows.

Aucun outil de developpement n'est necessaire.

## Important

Sur GitHub, n'utilisez pas le bouton vert `Code`, puis `Download ZIP`.

Ce bouton telecharge seulement les fichiers de presentation du depot public
(`README`, `CONTACT`, etc.). Il ne contient pas l'application.

Pour telecharger le programme, il faut utiliser la page `Releases` et prendre
le fichier Windows place dans la section `Assets`.

## 1. Aller sur la page de telechargement

Ouvrez cette page dans votre navigateur :

https://github.com/netbaren/jAstroLazCore_release/releases

La page affiche la derniere version disponible.

## 2. Telecharger le fichier Windows

Dans la section `Assets`, telechargez uniquement le fichier dont le nom
ressemble a :

```text
jAstroLaz-win64-xxxxxxx.zip
```

Exemple :

```text
jAstroLaz-win64-6a74da7.zip
```

Ne telechargez pas :

- `Source code (zip)`
- `Source code (tar.gz)`

Ces deux fichiers sont ajoutes automatiquement par GitHub et ne contiennent pas
l'application Windows.

Le fichier sera generalement place dans le dossier `Telechargements`.

## 3. Copier le zip dans un dossier simple

Cette etape n'est pas obligatoire, mais elle evite de perdre les fichiers dans
le dossier `Telechargements`.

Dans l'explorateur de fichiers Windows :

1. Creez un dossier, par exemple `C:\jAstroLaz`.
2. Copiez le fichier `jAstroLaz-win64-xxxxxxx.zip` dans ce dossier.

## 4. Decompresser le fichier

Dans l'explorateur de fichiers Windows :

1. Faites un clic droit sur le fichier `jAstroLaz-win64-xxxxxxx.zip`.
2. Choisissez `Extraire tout...`.
3. Validez le dossier propose.

Il ne faut pas lancer le programme directement depuis le fichier zip. Il faut
d'abord le decompresser.

## 5. Lancer jAstroLazCore

Ouvrez le dossier obtenu apres decompression, puis double-cliquez sur :

```text
jastro_lazcore_app.exe
```

Le dossier `resources` doit rester dans le meme dossier que l'executable.

Au premier lancement, l'application peut creer ou mettre a jour ses caches.
Windows peut alors demander une ou plusieurs confirmations.

## Avertissement Windows

Au premier lancement, Windows ou l'antivirus peut afficher un avertissement
parce que l'application n'est pas signee avec un certificat commercial.

Si vous faites confiance au fichier telecharge :

1. Cliquez sur `Informations complementaires`.
2. Cliquez sur `Executer quand meme`.

Selon l'antivirus utilise, il peut aussi etre necessaire d'autoriser le fichier
ou de confirmer qu'il peut etre execute.

## En cas de probleme

Verifiez d'abord les points suivants :

- le fichier telecharge est bien `jAstroLaz-win64-xxxxxxx.zip` ;
- le fichier n'est pas `Source code (zip)` ;
- le fichier zip a bien ete decompresse avant de lancer l'application ;
- le dossier `resources` est toujours present a cote de `jastro_lazcore_app.exe`.

## Contact

Pour une question ou un retour, voir [CONTACT.md](CONTACT.md).
