**Depends on macchanger!**

###INSTALL
    cp macchanger.sh /usr/local/bin
    cp macchanger.service /lib/systemd/system
    systemctl enable macchanger.service

###SETUP
    vim /usr/local/macchanger.sh
Default interface is wlan0, change this if your interface is different.

###TODO
Rewrite script to use iproute2 instead of macchanger?
Create a configuration file to store variables? (interface, randomization method..)