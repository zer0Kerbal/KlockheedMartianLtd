---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
Klockheed Martian Ltd (KML)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

## [Klockheed Martian Ltd (KML)][mod]

[Home](./index.md)

*Our mission is Kerbol*

Agent, flags, and common files for Klockheed Martian.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `KlockheedMartian` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/KlockheedMartian/KlockheedMartianLtd`
* Extract the package's `KlockheedMartian` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/KlockheedMartian` --> `<KSP_ROOT>/GameData/`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/KlockheedMartian/KlockheedMartianLtd`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/KlockheedMartian/KlockheedMartianLtd`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/KlockheedMartian/KlockheedMartianLtd`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [KlockheedMartian]
      + [KlockheedMartianLtd]
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
        * #.#.#.#.htm
        * Attributions.htm
        * CC-BY-ND-4.0.txt
        * changelog.md
        * KlockheedMartianLtdLtd.version
        * ManualInstallation.htm
        * readme.htm
    ...
    * [Module Manager][mm] or [Module Manager /L][mml]
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```
  
### Dependencies
  
* none
