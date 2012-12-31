AXE
===

The AXE script

Requirements .... 
1) a fresh archlinux install onto a x86 / x64 box, with dhcpd enabled
2) a fast stable, wired internet connection, not static or overly complex.
3) you need to be sure your network hardware is linux compatible
4) get me to /usr/bin , executable
   easiest way to do that is to, from the target system
   .> pacman -Syu
   .> pacman -S unzip wget
   .> wget https://github.com/Jubei-Mitsuyoshi/AXE/archive/master.zip && unzip -j AXE-master.zip && cp -pf /AXE-master/AXE-SCRIPT/axe /usr/bin/axe && rm -fr AXE-master*
 5) a good knowlege of linux, archlinux