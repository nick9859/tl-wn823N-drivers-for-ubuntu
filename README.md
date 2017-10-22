# tl-wn823N-drivers-for-ubuntu
TP-LINK tl-wn823N usb adapter - drivers for ubuntu

Those drivers can be found at the official TP-LINK site:
http://www.tp-link.com/us/download/TL-WN823N.html#Driver

But they didn't compile at my computer because there were many errors...

I edited some parts of the code so that gcc don't produce any errors anymore.
Hopefully all files needed compiled successfully (still some warnings from gcc though). Installation seems to be successful, too.

## Steps for installing the drivers: </br>
1) Compile
`sudo make` </br>
2) Install
`sudo make install`
