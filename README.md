# rdpcheck-cybzen v0.1

sha256 hash 524c6efd53864c72eacc8c94a82b2196753bf00026c013494990bbdcbec4aad6

rdpcheck-cybzen is a small BASH script which tests a series of usernames and passwords against an RDP host. I have included instructions on how to setup what is required and in this case using a Raspberry Pi 5 (although this should work on any release of Linux that includes the right tools).

WARNING - always get written permission before you test usernames and passwords against an RDP host. This script has no warranty, use at your own risk!

# Instructions

1. Create a KALI image on an SD-CARD using balenaEtcher. There us a stable KALI image for Raspberry Pi ARM
2. Boot the image on your Raspberry Pi
3. Login as root
4. Add a user using adduser and switch that user
5. Open a standard command prompt
6. Download rdpcheck-cybzen and userpasslist
7. Edit rdpcheck-cybzen and change host="x.x.x.x" to your rdp host IP or DNS name
8. Edit userpasslist and added usernames(s) and password(s) you wish to test
9. Run rdpcheck-cybzen .\rdpcheck-cybzen userpasslist
10. A successful connection will end with the host window showing

