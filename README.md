# arduno-yun-universal-remote
Some details on the build of an Arduino Universal Remote

It took a fair amount of googling and browsing so I am going to try and consolidate some of this information into one place

following this guide:

http://makezine.com/projects/smart-remote-control/


helpful links: 

http://wiki.linino.org/doku.php?id=wiki:gettingstarted

http://www.arduino.cc/en/Tutorial/YunSysupgrade

http://download.linino.org/linino_distro/master/latest/

http://www.ibuyopenwrt.com/index.php/8-yun-compatible/104-reset-to-factory-settings



Passwords: 
linino - linion, doghunter
arduino - arduino

Pitfalls:
opkg update fails with "Remove wrong Signature file"
- This error seems to happen when Ethernet/Wi-Fi have a problem or are both connected. best option I have found to fix the issue is to do a fresh install of the firmware and reconfigure the yun. Do not connect it to the Ethernet and use only the wifi. (or vice versa) 
