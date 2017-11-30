# guacamole-centos-install

Clone and execute script
```
wget https://raw.githubusercontent.com/paulphoenix01/guacamole-centos-install/master/guacamole-install-script.sh
chmod +x guacamole-install-script.sh
./guacamole-install-script.sh
```
Enter password following the wizard.

Login with default pw guacadmin:guacadmin and change

Access with url
```
http://x.x.x.x:8080/guacamole
https://x.x.x.x:8443/guacamole
```

Menu bar shortcut key: Ctrl + Shift + Alt
Disable fw if necessary
```
systemctl disable firewalld
reboot
```

