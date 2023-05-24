This pack includes several components, which is the latest version of Hekate, Atmosphere, Tinfoil and Signature patches  and some payloads like the latest version of Lockpick_RCM, and Tegraexplorer along with its Scripts. This pack also contains the SX Gear 1.1 Boot.dat file. 

## HOW TO INSTALL THE PACK

Watch this : https://www.youtube.com/watch?v=jfJIVzeJSyE

1. Delete the existing Atmosphere, Config , Bootloader, Sept folder from your SD card
2. Extract the HATS pack to your SD card
3. Inject the SX Loader Payload for unpatched Switch or just boot the console for all patched Switch including the Lites
4. You will then boot to Hekate. Press launch and choose whatever environment you are going to load.



## HOW TO UPDATE THE PACK

- Delete the previous files or just replace it with the new downloaded pack, as easy as that.

## HOW TO UPDATE THE CONSOLE FIRMWARE
- Please watch this video https://youtu.be/W_OjR-yxfdY



## ABSOLUTE LINK

Use this link to always download the updated pack
https://link.sthetix.info/hats


## WHY IS IT CALLED HATS ?

Well, it contains (H)ekate + (A)tmosphere + (T)infoil + (S)uper . Easy to remember, right?

## WHAT IS SYSMMC / EMUMMC / STOCK

- STOCK is OFW. It is the actual factory firmware that comes from the factory
- SYSMMC is OFW with patches or CFW. You can run homebrews on it but do not install game backups on this world unless you know what you are doing and its consequences. It reflects the OFW/STOCK itself. 
- EMUMMC is the emulated SYSMMC. It copied itself from the OFW and placed inside the micro SD card, and it is always in the CFW method. It is unrelated to the STOCK/OFW/SYSMMC as it is a different entity after creation. You can install and run anything here, like game backups, homebrews, etc. 

## HOW TO USE THE PACK WISELY AND NOT GET BANNED

- Do not install game backups or run Tinfoil on the SYSMMC, as it reflects the OFW. If you accidentally installed those stuff, please do the SYSTEMWIPE immediately: https://youtu.be/n6xEakq3n58
- Install game backups and others under the EMUMMC mode
- You can connect the SYSMMC and the EMUMMC to the internet as the exosphere.ini hides the console's serial number on all CFW modes
- To connect the SYSMMC to the e-shop or the Big N server, you must edit the exosphere.ini file and alter the blank_prodinfo_sysmmc=1 to blank_prodinfo_sysmmc=0. Make sure you know what you are doing and know the consequences of doing this.
- Do not use cheats on online games (like the splatoon 3)


## HOW TO BOOT TO ANY CFW MODE FROM HEKATE

To boot to any CFW mode, please follow this guide.

![cfw](https://github.com/sthetix/HATS/blob/main/cfw.png)

## HOW TO BOOT TO THE REAL STOCK (OFW) FROM HEKATE

To boot to real stock, please follow this guide 
because launching OFW from the Launch menu is NOT the real stock, but semi-stock as stated here https://github.com/CTCaer/hekate/blob/master/res/hekate_ipl_template.ini

![stock](https://github.com/sthetix/HATS/blob/main/stock.png)

## HOW TO TRANSFER FILES INTO/FROM YOUR CONSOLE TO YOUR COMPUTER WIRELESSLY

1. Make sure you have connected your console to your home network
2. Open the album
3. Press Y  to find the IP address of your console
4. Open any FTP manager on your computer
5. Connect to the IP address shown on your console on port 5000 with username/password: switch/switch

## ERROR 2023-0011 SOLUTION

![2023-0011](https://github.com/sthetix/HATS/blob/main/2023-0011.png)

The HATS pack hides the console's serial number on all CFW modes. That is why if you launched the sysMMC or the emuMMC and tried to connect the console to eshop or update the games online, you will see this error code.
To solve this issue, please boot to the OFW mode https://github.com/sthetix/HATS#how-to-boot-to-the-real-stock-ofw-from-hekate

## HOW TO CONNECT THE CONSOLE TO THE NINTENDO SERVER WHILE RUNNING THE CFW MODE

As mentioned, the HATS pack hides the console's serial number on all CFW modes to prevent your console from getting banned online if you accidentally / unintentionally installed pirated or illegal apps/games.
However, if you insist on connecting the CFW modes to the Nintendo server, you must edit the exosphere.ini at the root of the SD card with a notepad.

To connect the sysMMC to the Nintendo server, please edit

*blank_prodinfo_sysmmc=1 to blank_prodinfo_sysmmc=0*

To connect the emuMMC to the Nintendo server, please edit

*blank_prodinfo_emummc=1 to blank_prodinfo_emummc=0*


## HOW TO CREATE YOUR OWN HATS PACK

1. Download the latest Atmosphere from https://github.com/Atmosphere-NX/Atmosphere/releases
2. Download the latest Hekate from https://github.com/CTCaer/hekate/releases
3. Download the latest signature patches from https://sigmapatches.coomer.party/
4. Download the latest Tinfoil from Tinfoil.io
5. Download the latest DBI from https://github.com/rashevskyv/dbi/releases
6. Download the SX Gear boot.dat and boot.ini from https://u.pcloud.link/publink/show?code=XZCMlYXZNIJUnyr352XVWoXCuPo2SmwsRGpk
7. Download the hekate_ipl.ini and its graphic resource from: https://u.pcloud.link/publink/show?code=XZAkVUXZkgrREaCGTQLsTYfCeUqXFhKDnfBk
8. Create the DBI folder inside the Switch folder and put the latest DBI into it (the .nro and its .config)
9. Download any tools/homebrew apps you want to add to the pack
10. Combine them all together, like extract them all into a folder, put the payloads file inside the bootloader folder








## CREDIT

[CTCaer](https://github.com/CTCaer)
[Atmosphere-NX](https://github.com/Atmosphere-NX)
[Blawar](https://github.com/blawar)
[ITotalJustice](https://github.com/ITotalJustice)
[suchmememanyskill](https://github.com/suchmememanyskill)
[shchmue](https://github.com/shchmue)
[rashevskyv](https://github.com/rashevskyv)
[fortheusers](https://github.com/fortheusers)
[Werwolv](https://github.com/WerWolv)
[carcaschoi](https://github.com/carcaschoi)
[HamletDuFromage](https://github.com/HamletDuFromage)
[dezem](https://github.com/dezem)
[hwfly-nx](https://github.com/hwfly-nx)
[cathery](https://github.com/cathery)
[jits](https://jits.cc)
[titz](https://titz.cf)
[stealtshop](https://stealthshop.cf)
[quotanx](https://quotanx.in)
[pengu](https://pengu.us)
[teknik](https://teknik.app)
[DarkMatterCore](https://github.com/DarkMatterCore)
[J-D-K](https://github.com/J-D-K)
[tomvita](https://github.com/tomvita)
[proferabg](https://github.com/proferabg)
[masagrator](https://github.com/masagrator)
[SunResearchInstitute](https://github.com/SunResearchInstitute)
[SegFault42](https://github.com/SegFault42)
[mtheall](https://github.com/mtheall)
[joel16](https://github.com/joel16)
[XorTroll](https://github.com/XorTroll)
[proferabg](https://github.com/proferabg)
[rdmrocha](https://github.com/rdmrocha)


