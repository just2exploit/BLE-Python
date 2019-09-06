# Find Characteristic of any BLE Device
To find the Characteristic of a BLE device
Install pygatt for python3

sudo apt-get install python3-pip

sudo pip3 install pygatt

USAGE
Use Bluehydra or hcitool to scan your target BLE device and copy the BD_ADDR of the target device. Then run the programm as we usually run python3

sudo python3 character.py

Then it will ask for the user to enter the BD_ADDR of the target device, just paste the BD_ADDR of the target device which is found using Bluehydra or hcitool, then it will display all the characterstic of the device indicating all characterstic adapted by Bluetooth SIG.
