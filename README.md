**Depends on macchanger!**

###INSTALL
    cp macchanger.sh /usr/local/bin
    cp macchanger.service /lib/systemd/system
    systemctl enable macchanger.service

###SETUP
    vim /usr/local/macchanger.sh
Default interface is wlan0, change this if your interface is different.
