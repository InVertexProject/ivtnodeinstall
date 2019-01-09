Introduction

This script is for a single masternode setup, on a Ubuntu 16.04 64bit server (VPS) running headless and will be controlled from the wallet on your local computer (Control wallet). The wallet on the the VPS will be referred to as the Remote wallet.

Basic requirements

- 5,000 IVT
- A main computer (Your everyday computer) – This will run the control wallet, hold your collateral 5,000 ivt and can be turned on and off without affecting the masternode.
- Masternode Server (VPS – The computer that will be on 24/7)
- A unique IP address for your VPS / Remote wallet

Script start

- Generate masternode key from the wallet debub console by command 'createmasternodekey'
- Copy ivtinstall.sh file into the targeted installation directory on Masternode Server
- Run command ./ivtinstall.sh
- Answer on questions in the script
- Paste generated key from the first step

