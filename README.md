## Installation

1. For Windows on PowerShell :

   ```
   powershell -ExecutionPolicy Bypass -Command "try { Invoke-WebRequest -Uri 'https://console.icn.global/downloads/install/start.ps1' -OutFile '.\start.ps1' -UseBasicParsing; &     '.\start.ps1' -PrivateKey '<private_key>'} finally { Remove-Item .\start.ps1 -ErrorAction SilentlyContinue }"
   ```
- Replace your <private_key> with your private key address burned
   ```

2. For Linux/MAC :

   ```
   curl -o- https://console.icn.global/downloads/install/start.sh | bash -s -- -p <private_key>
   ```
- Replace your <private_key> with your private key address burned
