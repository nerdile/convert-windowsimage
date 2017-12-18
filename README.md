# convert-windowsimage
Scripts for converting Windows images (ISO,WIM) to VHD's

This is a fork of Convert-WindowsImage from the TechNet ScriptCenter: https://gallery.technet.microsoft.com/scriptcenter/Convert-WindowsImageps1-0fe23a8f

This code is owned by Microsoft and licensed under the MS-LPL.  See the LICENSE file for more information.

## Changes from the ScriptCenter version
- Fix for error on Win10 1709: ERROR  : Exception calling "Apply" with "1" argument(s): "The directory or file cannot be created"
- Make it runnable as .\Convert-WindowsImage.ps1 ... by binding the parameters at the script level, instead of declaring a function inside a script
