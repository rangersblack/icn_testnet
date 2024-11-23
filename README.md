# icn_testnet
# for windows on powershell
  powershell -ExecutionPolicy Bypass -Command "try { Invoke-WebRequest -Uri 'https://console.icn.global/downloads/install/start.ps1' -OutFile '.\start.ps1' -UseBasicParsing; & '.\start.ps1' -PrivateKey '<private_key>'} finally { Remove-Item .\start.ps1 -ErrorAction SilentlyContinue }" 

  Replace <private_key> with your private key.

  # for linux 
  curl -o- https://console.icn.global/downloads/install/start.sh | bash -s -- -p <private_key>   
  Replace <private_key> with your private key.
