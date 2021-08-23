# DotnetInstalled
checks whether the .net 4.8 version is installed on the user's computer.

## Goal
If a dll written in C# is used by another project written in object pascal, it is used to install and restore the .net dll on the user's computer.

function FindDotNetVersion:
```javascript
function FindDotNetVersion : TDotNetFrameWorkVersions;
```
Finds the .net version installed on the computer.

function TDotNet.IsInstalled: Boolean; 
```javascript
function function IsInstalled : Boolean;
```
It checks if IsInstalled is installed with the function.
function Install
```javascript
function Install : Boolean;
```
.net loads
function DownloadFile
```javascript
function DownloadFile : Boolean;
```
.net is dowlanded.
function RegisterDLL
```javascript
function RegisterDLL(const AFileName : String) : Boolean;
```
used to register dll
## Used Technologies
- Delphi 7
- object pascal
