Step by Step procedure to create a wifi Access point on Raspberry pi 3:

This directory has scripts that makes necessary changes to interfaces files, installs hostapd and configures it to make the raspberry pi as a wifi access point. I made few changes and modified scripts obtained from various sources to make the code work as one piece.

sudo git clone https://github.com/hemanthpratury/Wifi-Access-Point-for-RaspberryPi3.git

sudo chmod +x install.sh

sudo chmod +x ap.sh

sudo ./install.sh

sudo ap <AccessPointName> <Password>
