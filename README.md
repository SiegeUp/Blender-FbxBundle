# Fork of FBX Bundle Addon tweaked for SiegeUp 3d Workflow

In order to export building or decoration:
1. Install addon in Edit -> Preferences -> Add-ons -> Install
2. In Add-on settings check only modifier "Merge" in modifiers sections
3. Setup output directory for the files (it should be located somewhere inside Unity/Assets for quick import)
4. Create empty object with scale = 1 and set a name for it
5. Select all objects, related to a building or decoration and make child of an empty object using Ctrl+P
6. Select any child object and click Export 
7. You will see your new object in Unity, now you can setup material and use in your mods

![](https://github.com/SiegeUp/Blender-FbxBundle/raw/master/SiegeUpDocs/HowToExport.png)


![](https://farm2.staticflickr.com/1775/43061827304_ef4d3f99be_o.png)

# FBX Bundle Addon #

The **FBX Bundle** Addon is a **Blender 2.8** addon that simplifies the process of batch exporting FBX files. It's easy to use: specify a folder, select your objects, press 'Export'. FBX files for Unity will have correct rotations and scale values assigned as well as automatically existing materials assigned if their names match with Blender's materials per object.

This is an unofficial port to blender 2.8

## Documentation & Releases ##
You can find documentation and the previous releases on the official website

* [renderhjs.net/fbxbundle](http://renderhjs.net/fbxbundle)


# Release Log #

## FBX Bundle 1.5.2 ##
* Added a fix for the re-export button.
* There might be some issues with enabling collections before the export happens.
* LodGroup fixes

## FBX Bundle 1.5.1 ##

**WARNING**

* Experimental port to blender 2.8.
* Please backup your work before using this tool!

**Download**

* [FBX_Bundle_1.5.1.zip](https://github.com/TiliSleepStealer/blender-addon-fbx-bundle/releases/download/release_1.5.1/FBX_Bundle_1.5.1.zip)

## FBX Bundle 1.5.0 ##

**Download**

* [FBX_Bundle_1.5.0.zip](http://renderhjs.net/fbxbundle/download/FBX_Bundle_1.5.0.zip)

**Changes**

* New modifiers: Rename, Offset transform, copy modifiers, merge meshes, collider meshe, LOD, vertex AO
* New platform system: Unity, Unreal, Collada, glTF
* glTF support (requires official glTF addon)
* New pivot mode: Empty plain axis object
* Include children: Auto select grouped objects e.g. in scene mode, group mode, parent mode
* Re-Export button: Re-Exports previous objects again

## FBX Bundle 1.2.0 ##

**Download**

* [FBX_Bundle_1.2.0.zip](http://renderhjs.net/fbxbundle/download/FBX_Bundle_1.2.0.zip)

**Changes**

* New pivot mode: parent pivot
* improved Unreal & Unity export & smoothing groups
* fixed scale for Unreal export
* install / uninstall errors fixed
* New mesh fix tool: clean up smoothing, uv & topology issues on selected objects

## FBX Bundle 1.1.0 ##

**Download**

* [FBX_Bundle_1.1.0.zip](http://renderhjs.net/fbxbundle/download/FBX_Bundle_1.1.0.zip)

**Changes**

* Rotate meshes x -90 to counter rotation issues in Unity
* New pivot mode: lowest object
* Warning if scene units are not metric
* New merge mode added
* New Unity Editor script to process fbx 

## FBX Bundle 1.0.0 ##

**Download**

* [FBX_Bundle_1.0.0.zip](http://renderhjs.net/fbxbundle/download/FBX_Bundle_1.0.0.zip)

**Changes**

* initial release
* export & import from a set folder
* draw fences tool
