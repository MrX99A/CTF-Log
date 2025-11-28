# CTF-Log
Here's my log practice CTF and journal

#Mr-Robot 1 11/5/25
Windows, Seems blocking the ova of this file and marked as trojan so i exclude the extension ova from vulnhub to allow me to download the file hopefully its save.
A sweet beginning for newbie, i've learn a lot stuff but this time to practice, not learn but do, since experience is more matter than knowledge in some area.

Problems - Internal Network
Internal network seems to not connected properly, so its need to be activated manualy from command prompt. Luckly there's some tutorial from networkchuck.

Enabling the Internal Network of VirtualBox:
- ``cd /Program Files/Oracle/VirtualBox``
- ``vboxmanage dhcpserver add --network=internal/(nameoftheinternalnetwork) --server-ip=10.35.1.1 --lower-ip=10.35.1.100 --upper-ip=10.35.1.200 --netmask=255.255.255.0 --enable``
