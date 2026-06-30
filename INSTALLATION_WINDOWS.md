# Installing jAstroLazCore on Windows

This page explains how to download, install and start jAstroLazCore on Windows.

No development tool is required.

## Important

Do not use `Code` > `Download ZIP`.

That archive only contains the public repository documentation (`README`,
`CONTACT`, etc.). It does not contain the application.

To download the program, use the `Releases` page and take the Windows file from
the `Assets` section.

## 1. Open the download page

Open the jAstroLazCore release page:

https://github.com/netbaren/jAstroLazCore_release/releases

The page shows the latest available version.

## 2. Download the Windows file

In the `Assets` section, download only the file named like:

```text
jAstroLaz-win64-xxxxxxx.zip
```

Example:

```text
jAstroLaz-win64-6a74da7.zip
```

Do not download:

- `Source code (zip)`
- `Source code (tar.gz)`

Those two files are added automatically by GitHub and do not contain the Windows
application.

Depending on the browser, the file is usually saved in the `Downloads` folder.

## 3. Copy the zip file to a simple folder

This step is optional, but it avoids losing the files in the `Downloads` folder.

In Windows File Explorer:

1. Create a folder, for example `C:\jAstroLaz`.
2. Copy the `jAstroLaz-win64-xxxxxxx.zip` file into that folder.

## 4. Extract the zip file

In Windows File Explorer:

1. Right-click the `jAstroLaz-win64-xxxxxxx.zip` file.
2. Choose `Extract All...`.
3. Confirm the proposed folder.

Do not run the program directly from inside the zip file. It must be extracted first.

## 5. Start the application

Open the extracted folder, then double-click:

```text
jastro_lazcore_app.exe
```

Keep the `resources` folder in the same folder as the executable.

On first launch, the application may create or update its cache files. Windows
may ask for one or more confirmations.

## Windows security warning

Windows or the antivirus may display a warning the first time the program is
started because the application is not signed with a commercial certificate.

If you trust the downloaded file:

1. Click `More info`.
2. Click `Run anyway`.

Depending on the antivirus, you may also need to allow the file or confirm that
it can be executed.

## Troubleshooting

First check the following points:

- the downloaded file is really `jAstroLaz-win64-xxxxxxx.zip`;
- the file is not `Source code (zip)`;
- the zip file has been extracted before starting the application;
- the `resources` folder is still next to `jastro_lazcore_app.exe`.

## Contact

For questions or feedback, see [CONTACT.md](CONTACT.md).
