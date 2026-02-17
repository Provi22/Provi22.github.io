---
title: "Tech"
permalink: /tech/
---

# Useful Links
These are useful tools that I've found online, they don't necessarily have to do with engineering or my projects, just stuff I've found useful in the past.

- <a href="https://ezconv.cc/" target="_blank" rel="noopener noreferrer">YouTube to MP3</a>

- <a href="https://app.clipchamp.com/login" target="_blank" rel="noopener noreferrer">Clipchamp</a>

- <a href="https://wiiu.hacks.guide/" target="_blank" rel="noopener noreferrer">Wii-U Hombrew</a>

- <a href="https://pretendo.network/" target="_blank" rel="noopener noreferrer">Wii-U online servers</a>

- <a href="https://perrohuevo.wixsite.com/theme-cafe/" target="_blank" rel="noopener noreferrer">Wii-U custom themes</a>

- <a href="https://marcrobledo.com/RomPatcher.js/" target="_blank" rel="noopener noreferrer">Rom Patcher JS</a>

- <a href="https://cameronsino.com/product-verification.html/" target="_blank" rel="noopener noreferrer">Cameron Sino Product verification</a>

- <a href="https://remotexy.com/en/editor/" target="_blank" rel="noopener noreferrer">Remote XY</a>

- <a href="https://scribd.com/document/873201139/MBenz-C240-C280-W202-M112-Repair" target="_blank" rel="noopener noreferrer">Mercedes M112 Repair Manual</a>

- <a href="https://beatsync.gg/" target="_blank" rel="noopener noreferrer">Beatsync</a>

- <a href="https://animagraffs.com//" target="_blank" rel="noopener noreferrer">Animagraffs</a>

- <a href="https://acer.com/us-en/support/product-support/" target="_blank" rel="noopener noreferrer">Acer product support</a>

- <a href="https://neapay.com/online-tools/credit-card-number-generator-validator.html" target="_blank" rel="noopener noreferrer">CC Generator and validator</a>

---

# Windows troubleshooting
Common stuff I've used while troubleshooting in Windows 10/11

---

## Windows Apps / CMD and Powershell commands
```
diskpart
```
Manages disks and partitions directly from the Windows command line, giving you more control than the disk management app. Learn how to use it <a href="https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/diskpart" target="_blank" rel="noopener noreferrer">here</a>.


```
chkdsk
```
Checks and fixes disk errors and file system issues. Learn how to use it <a href="https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/chkdsk?tabs=hdd%2Cevent-viewer" target="_blank" rel="noopener noreferrer">here</a>.


```
powercfg /batteryreport /output "C:\battery-report.html"
```
Generates a detailed battery health report and saves it as an HTML file.


```
SFC /scannow
```
Scans and repairs corrupted Windows system files.


```
Win+R: MRT
```
Opens the Windows Malicious Software Removal Tool to scan for common threats.


```
Win+R: Shell:appsfolder
```
Opens the folder showing all installed apps and programs on your PC, even hidden ones on the settings app, letting you uninstall bloatware.


```
Win+R: mdsched.exe
```
Runs the Windows Memory Diagnostic to check for RAM problems.


```
& ([scriptblock]::Create((irm "https://debloat.raphi.re/")))
```
A simple way to debloat windows. Downloads and runs a script from this github repository: github.com/Raphire/Win11Debloat