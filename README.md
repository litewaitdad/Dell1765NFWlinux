# Dell1765NFWlinux
Linux printing easily w/ Dell 1765NFW on Debian or other debian based OS's


Following was done on Debian 11--

Install snapstore:

sudo apt update
sudo apt install snapd
sudo snap install core
sudo snap install snap-store


Install Ghostscript-printer-app:

sudo snap install ghostscript-printer-app --edge


Install this Snap, go to http://localhost:8000/ (or to http://localhost:8001/, ... if you have more than one Printer Application installed).. CUPS if already installed forces this to 8001.


Choose Xerox Workcentre 6015 Foomatic/foo2hbpl2 (reccomended) from driver dropdown..

Run test print

Printer should auto-share as air-print and to Mac OS via bonjour & visible via windows.




Many thanks to following information:
https://corion.net/blog/2021/11/12/getting-my-dell-c1765nf-to-work-on-debian/
https://snapcraft.io/ghostscript-printer-app
mirror of original foo2zjs: https://github.com/koenkooi/foo2zjs
