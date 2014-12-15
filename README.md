customwifipage
==============

* maak een aangepaste LOGIN.HTML

> zorg ervoor dat de javascriptcode 'submitAction' en zo erin staat - laatste stukje ook, hoewel niet duidelijk of dat nodig is

> kopieer form code

* maak tarbestand login.tar (! vanuit directory waar login.html staat werken !)

> tar -cvf ../login.tar .

* kopieer naar 192.168.2.22:/tftpboot

* Download naar controller

* Koppel login credentials aan SSID

> WLC -> Security -> AAA -> Local Net Users
