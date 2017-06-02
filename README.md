# EthMiningWindows
How to setup Ethereum mining on Windows and AMD graphics on the ethermine.org mining pool

- Download
Latest AMD Video Drivers
https://github.com/Genoil/cpp-ethereum/blob/master/releases/ethminer-0.9.41-genoil-1.1.7.zip
https://github.com/ethereum/mist/releases/download/v0.8.10/Ethereum-Wallet-installer-0-8-10.exe
And the file in this repository

- Setup
Install Ethereum-Wallet-installer-0-8-10.exe
Open and create a wallet on the MAIN network with a STRONG password.
Select the wallet and "Copy Address" of the wallet.

An example address is 0x0235601239B3cA6bBf8e07d900fC047149Ae54Ce

Extract ethminer-0.9.41-genoil-1.1.7.zip to any location
Download "run.bat" from this repository and place it in the extracted folder.
Open run.bat in a text editor and CHANGE the field <WALLET_ADDRESS> to your actual wallet address.
Change <MACHINE_ALIAS> to any name to identify your machine.

An example can be:
ethminer.exe --farm-recheck 200 -G -S us2.ethermine.org:4444 -FS us1.ethermine.org:4444 -O 0x0235601239B3cA6bBf8e07d900fC047149Ae54Ce.miner1

Run "run.bat"

Open your browser and visit https://ethermine.org/ and search for your wallet address.
You should now see the status of your miner.

