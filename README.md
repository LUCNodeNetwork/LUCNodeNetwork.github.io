Commands for setting up pi cluster:

sudo apt update

sudo apt full-upgrade

sudo apt install rpi-eeprom

sudo rpi-eeprom-update -a

sudo rpi-eeprom-config --edit

	Boot_order=Ox21
	
	tftp_ip=192.168.102.1
