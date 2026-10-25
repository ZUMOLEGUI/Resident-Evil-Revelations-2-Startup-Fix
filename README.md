# Resident-evil-revelations-2-Startup-Fix
Community troubleshooting guide for Resident Evil Revelations 2 startup crashes
Resident Evil Revelations 2 — Startup Fix

A community troubleshooting guide for a possible startup crash issue in Resident Evil Revelations 2 on PC.

The Problem

Resident Evil Revelations 2 may close unexpectedly when launching. This guide describes a possible workaround involving the legacy DirectX 9 component "d3dx9_43.dll".

Requirements

- A PC copy of Resident Evil Revelations 2.
- The official Microsoft DirectX End-User Runtimes (June 2010) package.

Official Microsoft download:
https://www.microsoft.com/en-us/download/details.aspx?id=8109

Instructions

1. Download the official DirectX End-User Runtimes (June 2010) package from Microsoft.
2. Extract the package contents to a temporary folder.
3. Locate the file "Jun2010_d3dx9_43_x86.cab".
4. Open the CAB archive and locate "d3dx9_43.dll".
5. Open Steam and go to your Library.
6. Right-click Resident Evil Revelations 2 and select Manage → Browse local files.
7. Copy "d3dx9_43.dll" into the game installation folder, where "re_rev2.exe" is located.
8. Launch the game and check whether the issue is resolved.

Important Notes

- This is an unofficial community troubleshooting guide.
- Obtain the DLL from the official Microsoft DirectX package rather than an untrusted third-party download.
- This workaround may not work for every system or configuration.
- If the game still crashes, try verifying the integrity of the game files through Steam.

Disclaimer

This project is not affiliated with or endorsed by Capcom, Valve, or Microsoft.

The procedure is provided for troubleshooting purposes, without any guarantee that it will resolve the issue.

Credits

Community-documented troubleshooting procedure.

Tested Result

Operating System: Windows 11
Game: Resident Evil Revelations 2 (PC)
File: "d3dx9_43.dll"

On my Windows 11 PC, Resident Evil Revelations 2 launched successfully after I copied "d3dx9_43.dll" from the official Microsoft DirectX End-User Runtimes (June 2010) package into the game's installation folder, next to "re_rev2.exe".

No CPU affinity changes, configuration file modifications, or custom injectors were used in this procedure.

Note: This workaround was tested on one Windows 11 system. Results may vary depending on the system configuration.
