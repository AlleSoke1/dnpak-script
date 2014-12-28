dnpak-script
============

DragonNest .pak extraction via quickbms script

This tool extracts all Resource00-11 from any dragonnest client.
It skips 0byte files (aka deleted files from updater).

It has 4 modes of extraction:
* 0 = Extract only DNT
* 1 = Extract only *.LUA\*.XML
* 2 = Extract all client resources\mapdata w/o:avi,ogg,dds,mp3,wav --For server configuration
* 3 = Extract all client resource\mapdata
