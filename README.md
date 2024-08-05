Rivalz AI Client CLI Guide
Hardware Requirements
CPU: 4 Cores (2.2GHz)
RAM: 4GB
Storage: 50GB
Internet: 1Mbps
System Update
Before installing the rClient, ensure your system is up-to-date:

bash
Копіювати код
sudo apt update && sudo apt upgrade -y
Installation and Setup
Install the Rivalz Node CLI:

bash
Копіювати код
sudo npm install -g rivalz-node-cli
Run the Rivalz Client:

bash
Копіювати код
rivalz run
Configuration:

Submit your EVM Address
CPU Core Number: Choose 50% of your total cores (e.g., if you have 4 cores, select 2 cores).
RAM Size: Allocate 60% to 70% of your total RAM.
Disk Type: Choose SSD.
Disk Serial Number: You can skip this field.
Disk Size: Choose 300GB or less.
Verification:

After running the client for 6 to 12 hours, you can verify your address here:

Rivalz Verification

Updating rClient
To update your rClient:

bash
Копіювати код
rivalz update
To check for available updates:

bash
Копіювати код
rivalz update-version
Help Command
For help and additional information:

bash
Копіювати код
rivalz -h
Uninstallation
To remove rClient:

bash
Копіювати код
rm -rf .rivalz
Source
For more details, refer to the Rivalz Documentation.
