# T440p-mac-oc
Version:20220328

Hackintosh OpenCore for Thinkpad T440P

Just support Mac Bis Sur 11.0.1

[![macOS](https://img.shields.io/badge/macOS-Big%20Sur-brightgreen.svg)](https://developer.apple.com/documentation/macos-release-notes)

### Prepare BIOS
The bios must be properly configured prior to installing macOS.
In Security menu, set the following settings:

-  `Security > Security Chip`: must be **Disabled**
-  `Memory Protection > Execution Prevention`: must be **Enabled**
-  `Internal Device Access > Bottom Cover Tamper Detection`: must be **Disabled**
-  `Anti-Theft > Current Setting`: must be **Disabled**
-  `Anti-Theft > Computrace > Current Setting`: must be **Disabled**
-  `Secure Boot > Secure Boot`: must be **Disabled**

In Startup menu, set the following options:

  
-  `UEFI/Legacy Boot`: **Both**
-  `UEFI/Legacy Priority`: **UEFI First**
-  `CSM Support`: **Yes**
### Install Your Mac Images
Cheak you mac Version must be Big Sur 11.0.1!!!!

