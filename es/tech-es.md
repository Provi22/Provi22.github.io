---
title: "Tech"
permalink: /tech/es/
---

# Enlaces útiles
Estas son herramientas útiles que he encontrado en línea, no necesariamente relacionadas con ingeniería o mis proyectos, solo cosas que me han resultado útiles en el pasado.

- <a href="https://ezconv.cc/" target="_blank" rel="noopener noreferrer">YouTube a MP3</a>

- <a href="https://app.clipchamp.com/login" target="_blank" rel="noopener noreferrer">Clipchamp</a>

- <a href="https://wiiu.hacks.guide/" target="_blank" rel="noopener noreferrer">Wii-U Hombrew</a>

- <a href="https://pretendo.network/" target="_blank" rel="noopener noreferrer">Servidores online de Wii-U</a>

- <a href="https://perrohuevo.wixsite.com/theme-cafe/" target="_blank" rel="noopener noreferrer">Temas personalizados para Wii-U</a>

- <a href="https://marcrobledo.com/RomPatcher.js/" target="_blank" rel="noopener noreferrer">Rom Patcher JS</a>

- <a href="https://cameronsino.com/product-verification.html/" target="_blank" rel="noopener noreferrer">Verificación de productos Cameron Sino</a>

- <a href="https://remotexy.com/en/editor/" target="_blank" rel="noopener noreferrer">Remote XY</a>

- <a href="https://scribd.com/document/873201139/MBenz-C240-C280-W202-M112-Repair" target="_blank" rel="noopener noreferrer">Manual de reparación Mercedes M112</a>

- <a href="https://beatsync.gg/" target="_blank" rel="noopener noreferrer">Beatsync</a>

- <a href="https://animagraffs.com//" target="_blank" rel="noopener noreferrer">Animagraffs</a>

- <a href="https://acer.com/us-en/support/product-support/" target="_blank" rel="noopener noreferrer">Soporte de productos Acer</a>

- <a href="https://neapay.com/online-tools/credit-card-number-generator-validator.html" target="_blank" rel="noopener noreferrer">Generador y validador de Tarjetas de Crédito</a>

---

# Solución de problemas en Windows
Cosas que he usado al solucionar problemas en Windows 10/11

---

## Aplicaciones de Windows / Comandos CMD y Powershell

```
diskpart
```
Gestiona discos y particiones directamente desde la línea de comandos de Windows, dándote más control que la aplicación de administración de discos. Aprende a usarlo <a href="https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/diskpart" target="_blank" rel="noopener noreferrer">aquí</a>.


```
chkdisk
```
Verifica y corrige errores del disco y problemas del sistema de archivos. Aprende a usarlo <a href="https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/chkdsk?tabs=hdd%2Cevent-viewer" target="_blank" rel="noopener noreferrer">aquí</a>.


```
powercfg /batteryreport /output "C:\battery-report.html"
```
Genera un informe detallado del estado de la batería y lo guarda como un archivo HTML.


```
SFC /scannow
```
Escanea y repara archivos de sistema de Windows dañados.


```
Win+R: MRT
```
Abre la Herramienta de Eliminación de Software Malicioso de Windows para buscar amenazas comunes.


```
Win+R: Shell:appsfolder
```
Abre la carpeta que muestra todas las aplicaciones y programas instalados en tu PC, incluso los ocultos en la app de configuración, permitiéndote desinstalar bloatware.

```
Win+R: mdsched.exe
```
Ejecuta el Diagnóstico de Memoria de Windows para comprobar problemas de RAM.


```
& ([scriptblock]::Create((irm "https://debloat.raphi.re/")))

```
Una forma sencilla de limpiar Windows de bloatware. Descarga y ejecuta un script de este repositorio de GitHub: github.com/Raphire/Win11Debloat
