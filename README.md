
THIS BIOS VERSION IS A PORT I MADE FOR REV 1.41 WITH 4305 OR NEWER BIOS VERSION
DONT FLASH INTO A 4304 OR OLDER CAUSE IT WILL BRICK YOUR BIOS AND YOU WILL NEED CH341 FOR UNBRICK.

My ports only WORKS WITH
REV 1.41V

new revs  like 1.41 and others not compatible . 
if you wanna a port, considere to DONATE.


Fixes:
New 152 With Bootsecure Port and TPM2 fix.


1 - Bootsecure

2 - TPM support

3 - Edk2 Shell Built-in  ( Flash Bios without SO and more)

4 - Smart Fan Menu Driver Fixed 

5 - Vroc 9 ported (RAID boot suported)

6 - Intel XPM ported ( OC Ram)

7 - Modern Status Code ( on screen boot)

8 - XTU supported 

9 - Bootime reduced from 20S to about 6 -12s depends of your nvme/hdd etc

10 - Retention C6 fixed

11 - OC by bios menu to 16XX v3 and I7 X 

12 - Integraded Rebar and Above 4G menu

13 - MacOS Opencore boot support

14 - 1st X99 to support M2 NVME SSD AHCI via PCIE adapter ( APPLE/SAMSUNG/OTHERS)

15 - Portuguese (BR) option to BIOS language.

and much much more.


LEGACY BIOS VERSION is for OLD GPU without UEFI GOP.



Donate and support this project!
[Donate Here!](https://www.paypal.com/donate/?business=CCB45NYKUULWE&no_recurring=0&item_name=Thanks+for+your+donate%21&currency_code=USD)
---

Thanks for @iC3H@CkER and @ShaneOss  for donates and beta test to make this project real
People like that can change the world!
**ATTENTION!**

**Different Types of Boards:**

There are two types of ZX-DU99D4 motherboards with significant hardware differences based on their BIOS versions:

1. **For motherboards with BIOS versions equal to or older than (05/06/2023) ZX-DU99D4 DU994304:**
   - You must first backup your BIOS using FPT. Download it [here](https://github.com/jwagnervaz/DUAL-CPU-ZX-DU99D4-V1.31-BIOSMOD/blob/main/FPT/FPT.zip) (Note: AFUWIN does not create a full backup BIOS).

2. **For motherboards with BIOS versions equal to or newer than (10/30/2023) ZX-DU99D4 DU994305:**
   - You must first backup your BIOS using FPT. Download it [here](https://github.com/jwagnervaz/DUAL-CPU-ZX-DU99D4-V1.31-BIOSMOD/blob/main/FPT/FPT.zip) (Note: AFUWIN does not create a full backup BIOS).
   - These have different hardware and BIOS compatibility.

**Important Notes:**
- Flashing the wrong BIOS version can result in errors (b7) or (61). and you will need a ch341 and flip to flash your bios chip with yout backup.
- If you get error  (AF), unplug the pc from power cord and press power for 5 seconds, this will erase your CMOS.
- To identify your BIOS version, check it in your BIOS settings. hit (DEL) when turn your PC on and discover your version.

**Compatibility Update:**
- I've created a port for motherboards with BIOS versions older than (05/06/2023) ZX-DU99D4 DU994304. REV 1.31 V and OLDER  [(HERE)](https://github.com/jwagnervaz/DUAL-CPU-ZX-DU99D4-V1.31-BIOSMOD/tree/main/PORT-VERSION-4304-OR-OLDER)
- This allows older motherboard owners to use newer BIOS versions like (03/06/2024)ZX-DU99D4 V1.3 DU994306 REV 1.41 [(HERE)](https://github.com/jwagnervaz/DUAL-CPU-ZX-DU99D4-V1.41-BIOSMOD/)
-  ZX-DU99D4 DU994305 AND NEWER DONT FLASH BIOS FROM HERE. I WILL DO MODS FOR THIS VERSION SOON AS POSSIBLE.



1- IM NOT REPONSSABLE FOR DAMAGES IN YOUR MOTHERBOARD, SO HAVE YOUR OWN DUMP AND A PROGRAMMER CH341 IF FOR SOME REASON YOU GET A BRICK
2- DO IT IN YOUR OWN RISK.
