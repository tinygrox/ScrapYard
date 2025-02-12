---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
ScrapYard (SYD)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# [ScrapYard (SYD)][SYD]

[Home](./index.md)

A common part inventory addon for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `ScrapYard` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/ScrapYard`
* Extract the package's `ScrapYard/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/ScrapYard` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/ScrapYard`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/ScrapYard`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/ScrapYard`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [ScrapYard]
      + [Agencies]
        ...
      + [Compatibility]
        ...
      + [Config]
        ...
      + [Flags]
        ...
      + [Localization]
        ...
      + [Plugins]
        ...
        ManualInstallation.htm
      * #.#.#.#.htm
      * Attributions.htm
      * changelog.md
      * GPL-2.0.txt
      * readme.htm
      * ScrapYard.version
    ...
    * [Module Manager /L][mml] or [Module Manager][mm]
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* *either*
  * [Module Manager /L][mml]
  * [Module Manager][mm]

[SYD]: https://forum.kerbalspaceprogram.com/index.php?/topic/192456-* "ScrapYard (SYD)"
[mm]: https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*/ "Module Manager"
[mml]: https://github.com/net-lisias-ksp/ModuleManager "Module Manager /L"