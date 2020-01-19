# LuaDataUpgrade
Upgrade any lua data file which is managed using **version number.**

## What:
Simple lua library which takes upgrade function and the data file to be upgraded.

## When:
When you have multiple lua datafile of same format and need changes in all the file or when move to new version with edited(addition/deletion)  data and need to update all the data file before actual using that data.

## How:
API : **UpgradeData(dataFile, fromVersion, toVersion)**
- dataFile : filepath of the lua data file which need to be updated
- fromVersion: either current version of data or from which version 
- toVersion: till which version upgrade need to be appllied.

## Library files: (LuaDataUpgrade namespace for the library)
1. DataUpgrade.lua
2. UpgradeFunctions.lua


MIT +> Copyright (c) <2020> <cyberCBM>
