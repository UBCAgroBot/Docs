### Connect to robot from distance via SSH 
1. Connect router to the jetson via Ethernet cable.
2. Connect to the wifi named Agrobot with password `agrobot2023!`.
3. Open a terminal on the jetson and lern the ip address using `hostname -I` command.
4. Open a terminal on your computer and use the `ssh ubcagrobot@<ip>` command to start a connection.

### Fix blue screen issue on Ubuntu / Jetson
1. Open a terminal (XTerm should still work)
2. Use the command `sudo dpkg --configure -a`
3. Reboot
