# WinformWorkTimeChecker

[![Windows](https://custom-icon-badges.demolab.com/badge/Windows-0078D6?logo=windows11&logoColor=white)](#)
[![C#](https://custom-icon-badges.demolab.com/badge/C%23-%23239120.svg?logo=cshrp&logoColor=white)](#)
[![.NET](https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=fff)](#)
[![NuGet](https://img.shields.io/badge/NuGet-004880?logo=nuget&logoColor=fff)](#)


## local publish
•    Framework‑dependent single file (recommended, smallest):
```
dotnet publish -c Release -r win-x64 -p:PublishSingleFile=true -p:SelfContained=false -p:PublishTrimmed=false -p:PublishReadyToRun=false -o ./publish
```
•    Self‑contained single file (bundles .NET runtime; larger):
```
dotnet publish -c Release -r win-x64 -p:PublishSingleFile=true -p:SelfContained=true -p:PublishTrimmed=false -p:PublishReadyToRun=false -o ./publish
```
