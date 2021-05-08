(Assuming you’ve got all the repos installed for access to kodi etc)

wget http://mirrors.kodi.tv/apt/atv2/deb/org.xbmc.kodi-atv2_14.2-0_iphoneos-arm.deb

wget http://mirrors.kodi.tv/apt/atv2/deb/org.xbmc.kodi-seatbeltunlock_1.0-5_iphoneos-arm.deb

wget http://ftp.ports.debian.org/debian-ports//pool-x32/main/b/bsdiff/bsdiff_4.3-21_x32.deb

wget http://ftp.ports.debian.org/debian-ports//pool-x32/main/g/gawk/gawk_5.0.1+dfsg-1_x32.deb

dpkg -i bsdiff_4.3-21_x32.deb

dpkg -i gawk_5.0.1+dfsg-1_x32.deb

apt-get -f install

apt-get update (if needed. it will auto reboot)

And if it errors, installing just use this command to install kodi

apt-get install org.xbmc.kodi-atv2