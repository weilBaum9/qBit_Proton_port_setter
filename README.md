# qBitTorrent port-setter

This repo contains a script that you can execute to start qBitTorrent with the currently set port in ProtonVPN.
You can also execute the same script to restart qBitTorrent with the correct port if you had do reconnect ProtonVPN while qBitTorrent was running (eg. disconect for an online game). You will probably have to install **psutil** using "pip install psutil". 

Modification Options:
- If you changed the installation path of either program you have to change the "config_file" and "log_file" variables in the script. 
- if you don't want the capability to restart qBit you can remove the "killQBit" method. psutil is just used in the killQBit Method so you can remove the import and won't have to install it with pip