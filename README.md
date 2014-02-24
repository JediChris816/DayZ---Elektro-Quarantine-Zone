DayZ---Elektro-Quarantine-Zone
==============================

DayZ, Elektro, Quarantine Zone


This is my Elektro Quarantine Zone addon.  Here is the link to view all images in my One Drive repository.  Please feel free to download and use.  Please do not take credit for work that is not yours.

Elektro Quarantine Zone addon -- http://1drv.ms/1ch27TT

You will need:
a: basic scripting/editing knowledge
b: PBO Manager 1.4 Beta to open your mission or server PBO. (download here if you don't have it, http://1drv.ms/1ch2RII)
c: a script/code editor.  I highly recommend Notepad++.  Download here, http://1drv.ms/1hLjgNx.


To add:

1.) Open your mission.PBO (you may need to download the PBO from your host ftp, if using HFB, or from the admin. control panel is using DayZ.ST).

2.) Next, open the init.sqf with Notepad++.

3a.) Scroll to the bottom of your init.sqf and add:
    [] execVM "ElektroQuarantineZone.sqf";
    
3b.) If you have a custom folder for map addons then you will need to adjust accordingly...
    [] execVM "YOUR CUSTOM FOLDER NAME HERE\Map_Addons\ChernoQuarantine_Zone.sqf";
    
4.) Be sure to save.  Save.  Save.

5.) Repack your mission.PBO using PBO Manager.

6.) Upload to server.

DONE!


