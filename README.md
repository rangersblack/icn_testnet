## Installation

1. For Windows on PowerShell :

   ```
   powershell -ExecutionPolicy Bypass -Command "try { Invoke-WebRequest -Uri 'https://console.icn.global/downloads/install/start.ps1' -OutFile '.\start.ps1' -UseBasicParsing; &     '.\start.ps1' -PrivateKey '<private_key>'} finally { Remove-Item .\start.ps1 -ErrorAction SilentlyContinue }"
   ```

   ```
   cd major-bot
   ```
