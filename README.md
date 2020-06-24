# Choco-Packages (tecRacer-MSP)
tecRacer MSP-Team based Chocolatey / Nuget Packages

## Folder overview

<pre>
chocolatey-packages
├── MSP.
│   ├── _MSP.packagename
│   │   ├── sb    
│   │   │   ├── 0.0.0.1    
│   │   │   │   ├── tools
│   │   │   │   │   ├── chocolateyinstall.ps1
│   │   │   │   │   └── chocolateyuninstall.ps1
│   │   │   │   │   └── .skipAutoUninstall
│   │   │   │   │   └── chocolateybeforemodify.ps1
│   │   │   │   │   └── helpers.ps1
│   |   │   │   │   ├── files
│   │   |   │   │   │   ├── xxxxx.msi
│   │   │   |   │   │   ├── xxxxx.msi.ignore
│   │   │   │   ├── sb.0.0.0.1.nupkg
│   │   │   │   └── sb.nuspec    
│   │   │   └── 0.0.0.2 
│   │   └── packagename2 
│   │   │   ...
│   │   └── packagename999
├── AWS.
│   ├── AWS.packagename
│   │   ├── 0.0.0.1
│   │   │   ├── tools
│   │   │   │   │   ├── chocolateyinstall.ps1
│   │   │   │   │   └── chocolateyuninstall.ps1
│   │   │   │   │   └── .skipAutoUninstall
│   │   │   │   │   └── chocolateybeforemodify.ps1
│   │   │   │   │   └── helpers.ps1
│   |   │   │   │   ├── files
│   │   |   │   │   │   ├── xxxxx.msi
│   │   │   |   │   │   ├── xxxxx.msi.ignore
│   │   │   ├── sb.0.0.0.1.nupkg
│   │   │   └── sb.nuspec    
│   │   └── 0.0.0.2
│   │   │   ...
│   ├── AWS.packagename2
│   │   │   ...
│   ├── AWS.packagename999
├── icons
│   ├── packagename.png
│   ├── packagename2.svg
│   │   ...
│   └── packagename999.png
├── licenses
</pre>

### Legend

#### MSP.
Direct landing strip for tecRacer MSP-Team chocolatey / Nuget Packages

#### AWS.
Direct landing strip for tecRacer MSP-Team made AWS applications / Drivers using chocolatey / Nuget Packages

#### icons
Package Icon files based on the Package Manifest - `<iconUrl>`
The URL that should be used should not point directly to the file.  Use this service http://rawgit.com/

#### licenses
Package Licesne (if applicable) based on the package Manifest - `<licenseUrl>`

### Package not working?
Provide the output of the following - `choco install PKGID --yes --verbose --debug`
Send to the info and anything else you have to the GitHub Issues section: https://github.com/sbrown-tecracer/choco-packages/issues/new
