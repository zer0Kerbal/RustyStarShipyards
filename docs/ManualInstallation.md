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

This part addon contains over one hundred parts made of rusty metal.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `RustyStarRockets` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/RustyStar/RustyStarRockets`
* Extract the package's `RustyStar/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/RustyStar` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/RustyStar/RustyStarRockets`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * you should end up with `<KSP_ROOT>/GameData/RustyStar/RustyStarRockets`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/RustyStar/RustyStarRockets`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [RustyStar]tion]
    + [RustyStarRockets]
      + [Compatibility]
        ...
      + [Config]
        ...
      + [Contracts]
        ...
      + [Localization]
        ...
      + [Parts]
        ...
      * #.#.#.#.htm
      * Attributions.htm
      * CC-BY-ND-4.0.txt
      * changelog.md
        ManualInstallation.htm
      * readme.htm
      * RustyStarRockets.version
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [Rusty Star Shipyards (RSS)][RSS]

[RSS]: https://forum.kerbalspaceprogram.com/index.php?/topic/209456-*/ "Rusty Star Shipyards"
[mm]: https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*/ "Module Manager"
[mml]: https://github.com/net-lisias-ksp/ModuleManager "Module Manager /L"
