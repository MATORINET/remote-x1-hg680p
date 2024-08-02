# remote-x1-hg680p
Config Remote X1 FirstMedia for Fiberhome HG680P

<img src="https://raw.githubusercontent.com/MATORINET/remote-x1-hg680p/main/remote%20x1.jpg" width="300" />

 Implementation Instructions:
 1. Check Factory code using command : dmesg | grep remote 
 2. Replace the Factory code ( 0x+(factorycode)+0001 ) with the actual codes from your remote
 3. Save this file as 'remote.conf' in /system/etc/ or /vendor/etc/
 4. Reboot the device
 5. 
