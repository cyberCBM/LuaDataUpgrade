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


Copyright (c) <2020> <cyberCBM>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
