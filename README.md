#Decrypt0r

###Rootfs decrypting

To decrypt rootfs or other components you have to get keys from https://www.theiphonewiki.com/wiki/Firmware_Keys. <br>

You have to enter the IPSW filename (ex : iPhone5,4_8.4.1_12H321_Restore.ipsw). <br>
The program will ask you to add the keys grabed from iphonewiki (only one for the rootfs). <br>

Then, the tool will decompress you'll have to add the rootgs name <br>
Next you have specify the name of the file containing rootfs (ex 058-24465-023.dmg). <br>
In the IPSW file, there is three dmg files, that of rootfs is heaviest. <br>

Then the program is going to work automaticaly. <br>

If you want to modify rootfs (ex Setup.app) you can use TransMac for Windows. <br>

### Encryption of rootfs and creating a Custom fimware

You can now create your own Custom fimware (need to work more). <br>
Downgrades are already impossible without SHSHs blobs, on devices that do not have low level exploits. <br>
Is this fonction useless ? <br>
Yes, but it can still be used. <br>

#Other components

To decrypt other firmware components like kernelcache or iBoot, you have to grab the keys from theiphonewiki <br>
The first one to add is the largest, and the second one is the iv key (the smallest) <br>

### How to build ?

To build Decrypt0r just cd to the decryptr0r directory and run  `make` <br> 

## TODO

- Work the improve custom firmwares <br>

## Credits

Thank you to my friend Jam Elrhk Elro ([@Elro74](https://twitter.com/Elro74)) for his Liberati0n script and help for dev. <br>
Developed by Mathieu Hautebas ([@matteyeux](https://twitter.com/matteyeux)) <br>
Thank you to [Callum Jones](https://twitter.com/icj_) for his awesome website ipsw.me and Neal (@iNeal) for his API.<br>

For this tool I used: <br>

- xpwn & dmg compiled from https://github.com/planetbeing/xpwn <br>
- 7zip (developed by Igor Pavlov) <br>

For more informations contact me on Twitter: [@matteyeux](https://twitter.com/matteyeux) or ask this [awesome website](http://www.google.com) <br>
