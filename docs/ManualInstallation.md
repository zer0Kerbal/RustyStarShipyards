---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
Rusty Star Shipyards (RSS)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# Rusty Star Shipyards (RSS)

[Home](./index.md)

Adds Rusty Star Shipyards's agent, flags, and common config files used in all Rusty Star Rockets add-ons for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `RustyStarShipyards` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/RustyStar/RustyStarShipyards`
* Extract the package's `RustyStar/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/RustyStar` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/RustyStar/RustyStarShipyards`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * you should end up with `<KSP_ROOT>/GameData/RustyStar/RustyStarShipyards`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/RustyStar/RustyStarShipyards`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [RustyStarShipyards]
      + [Agencies]
        ...
      + [Compatibility]
        ...
      + [Config]
        ...
      + [Localization]
        ...
      + [Resources]
        ...
      * #.#.#.#.htm
      * Attributions.htm
      * CC-BY-ND-4.0.txt
      * changelog.md
      * ManualInstallation.htm
      * readme.htm
      * RustyStarShipyards.version
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* none