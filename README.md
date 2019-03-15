
# [ResxManager](https://github.com/lbonifacius/resxmanager)

Consolidates, synchronizes and translates .NET resources (.resx, .wxl). Supports export to Excel (.xlsx) and automating translation.


# About [this fork](https://github.com/sandrock/resxmanager)

This fork will be used to create import/export features for [Markalize](https://github.com/sandrock/Markalize).

## Features

Those are the planned features:

- [ ] Export to Markalize's format
- [ ] Maybe more?

Those are the base features from the main repo.

- Translates any Visual Studio resource files (.resx) and Windows Installer XML toolkit localization files (.wxl)
- [Export and Import to Microsoft Excel (.xlsx)](docs/ExportImportResourcesToExcel.md) without having Excel installed
- Analysis of missing translations
- [Automatic translation](docs/AutomaticTranslation.md) using a custom translation database
- [Integration with Team Foundation Server (TFS)](docs/HowToUseWithTeamFoundationServer.md) **NEW**
- [Exclude Projects, Directories, Files or Entries from Translation](docs/ExcludeProjectsDirectoriesFilesEntries.md) by customizable patterns **NEW**
- No installation of Visual Studio required, so usable by non-devolopers as well as developers
- Portable application with simple user interface does not require an Installation

![](docs/Home_ResxManager001.png)

## Requirements

* Microsoft .NET Framework 4
* SQL Server 2012 (for translation storage only)

## Documentation

* [How to get started](docs/Documentation.md) 
