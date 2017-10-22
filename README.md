# tl-wn823N-drivers-for-ubuntu
TP-LINK tl-wn823N usb adapter - drivers for ubuntu

Those drivers can be found at the official TP-LINK site: <br>
http://www.tp-link.com/us/download/TL-WN823N.html#Driver

But they didn't compile at my computer because there were many errors...

I edited some parts of the code so that gcc don't produce any errors anymore.
Hopefully all files needed compiled successfully (still some warnings from gcc though). Installation seems to be successful, too.

## Steps for installing the drivers: </br>
1) Clone repository (`git clone https://github.com/nick9859/tl-wn823N-drivers-for-ubuntu.git`) or download it (https://github.com/nick9859/tl-wn823N-drivers-for-ubuntu/archive/master.zip) and unzip it <br>
2) Open a terminal into the new directory <br>
3) Compile using: <br>
`sudo make` <br>
4) Install using: <br>
`sudo make install`
