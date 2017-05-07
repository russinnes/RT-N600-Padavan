# RT-N600-Padavan
ASUS RT-N600 Router Firmware

This is custom firmware (Padavan) that has been built for the Asus RT-N600 Dual band AC Router.

Trying to update the stock firmware through the ASUS web GUI will NOT WORK!

###Instructions:###
1) Select the version you want (likely BASE)
2) -Download the Asus recovery firmware (windows) tool from http://dlcdnet.asus.com/pub/ASUS/LiveUpdate/Release/Wireless/Rescue.zip
   -Also works on a Windows VM with a bridged network adapter to the ethernet port with a manual IP)
   -Set your ethernet IP manually 192.168.1.100 / 255.255.255.0 with NO gateway
   
4) Plug in your ethernet to LAN port 1 on the router

5) Load up the recovery software with the selected firmware file from above, but dont press "Start Recovery"!

6) Plug in the router to power WHILE HOLDING the reset button in. While CONTINUING to hold the button, select "Start Recovery"
   Continue to hold the reset button in until it finishes and verifies!
   
7) The router will reboot and not much will happen. Wait a minute or 2. 

8) Power off and on the router again. Voila. Set everything back to DHCP and youre good to go. L:admin P:admin

   
 Source creds: https://bitbucket.org/padavan/rt-n56u/
 
* -BASE.trx:

  * USB
  * NTFS/FAT/EXT2/EXT3/FUSE
  * USB Audio
  * Parted
  * OpenVPN
  * SSH
  * USB Serial Driver
  
  
* -FULL.trx:

  * +Transmission
  * +Aria/2
  * +FFMpeg
  * +Firefly
  * +Minidnla
  * +L2TP
  * +SFtp
  * +Usb Printing
  

  
