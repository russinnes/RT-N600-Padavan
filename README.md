# RT-N600-Padavan
ASUS RT-N600 Custom Firmware (Padavan Base)

This is custom firmware (Padavan) that has been built for the Asus RT-N600 Dual band AC Router.

Trying to update the stock firmware through the ASUS web GUI will NOT WORK!

Instructions:
1) Select the version you want (I will build more with varying options shortly)

[RT-N600_3.4.3.9-099-A.trx:

  IPv6
  USB
  NTFS/FAT/EXT2/EXT3/FUSE
  USB Audio
  Parted
  Dropbear
  OpenVPN
  SSH
  
  
RT-N600_3.4.3.9-099-B.trx: (Coming Soon)

  All as Above Plus:
  Transmission
  Aria/2
  FFMpeg
  Firefly
  Minidnla
  L2TP
  SFtp
  USB-> Eth Printing
  
2) Download the Asus recovery firmware tool from http://dlcdnet.asus.com/pub/ASUS/LiveUpdate/Release/Wireless/Rescue.zip
   This runs on windows only (It also works with a windows VM with a bridged network adapter to the ethernet port on OSX)
   -If bridging through a VM host, set the host network adapter to a manual IP of 192.168.1.100 / 255.255.255.0 with NO   gateway
   
4) Plug in your ethernet to port 1 of the LAN on the router

5) Load up the recovery software with the selected firmware file from above, but dont press "Start Recovery"!

6) Plug in the router to power WHILE HOLDING the reset button in. While CONTINUING to hold the button, select "Start Recovery"
   Continue to hold the reset button in until it finishes and verifies!
   
7) The router will reboot and not much will happen. Wait a minute or 2. 

8) Power off and on the router again. Voila. Set everything back to DHCP and youre good to go. L:admin P:admin

   
 Source creds: https://bitbucket.org/padavan/rt-n56u/
  
