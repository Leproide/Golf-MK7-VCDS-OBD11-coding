![71189032_103998857673709_5961330266575208448_o](https://github.com/Leproide/Golf-MK7-VCDS-OBD11-coding/assets/8448713/42210268-e0e6-432d-9be5-2d8d0011e9b6)

# Golf-MK7-VCDS-OBD11-coding
Golf MK7/7.5 T-Roc T-Cross Polo etc coding. That's working on some Seat/Skoda/Audi on the same software/hardware platform

https://t.me/vagcodingitalia

------------

**MST2 activator by Congo & Duke with autobackup: Unit could be bricked**

**BEFORE YOU READ FURTHER:**

- On VW, press and hold MENU button on the display of your MIB2 for 3 seconds and then go to Software Update/Versions and take a look at SW Train string.

- On Audi use corresponding button combo to open RED menu and then look into Versions info

Make sure train starts with MST2 and ends with D. For example: MST2_EU_VW_P0891D. Only in this case, everything below applies to your unit!

![image](https://github.com/Leproide/Golf-MK7-VCDS-OBD11-coding/assets/8448713/5d6fafc3-2f8e-4806-be29-49812f2f9f17)

**If your SW Train ends with T (for example MST2_EU_VW_ZR_P0254T) your unit is Technisat/Preh for which you need MIB STD2 PQ/ZR Toolbox).**

Supported firmwares (trains)

All Audi and VW firmwares of any region with train matching pattern MST2_xx_xx_xxxxxD

Tested and confirmed FW versions: P0120D, P0123D, E0220D, P0225D, P0227D, E0231D, P0314D, P0504D, P0628D, P0631D, P0635D, P0642D, P9122D, P0867D, P0870D, P0876D, P0890D, P0891D, P0879D, P0883D

**Installation**

1. Format quality 4Gb+ SD card in FAT32 with the smallestcluster size possible ( usually4096 bytes)
2. Unpack [activator with autobackup](https://github.com/Leproide/Golf-MK7-VCDS-OBD11-coding/raw/main/MST2_Activator_Made_By_Congo_and_Duke_v3.0_with_Autobackup_by_lprot.7z "activator with autobackup") onto the SD card and make sure metainfo2.txt is in the root.
3. Turn the ignition on (VERY IMPORTANT! Without ignition on, the unit’s power will be automatically switched off after 30 minutes. Make sure the car battery is well charged or connect the charger!)
4. Insert SD card into SD1 slot,
5. Hold MENU button for 3 seconds to enter the Service Mode,
6. Select Software update/versions,
7. Select Update → SD card → MST2 Activator by Congo and Duke → Start → Next,
8. Wait. During the installation the unit will reboot 2 times. If you will see green window “Completed succsessfully” press and hold power on button to reboot the unit.
9. When the process is done you will see summary screen. Press Back in the upper-right corner,
10. When you see Version back documentation screen, press Cancel,and unit will reboot in normal mode.
11. If you install the version with autobackup, you will see green "Successfully completed” window. Just long press the power button to reboot the unit.
12. You can check log.txt in the root of SD card and if installed autobackup version - save backup folder to the safe place 😀

13. Ativation of App-Connect with VCDS/OBD11 etc...

5F → Long Coding → Byte: 19 → Bits: 6-7 → enable App-Connect compatible USB port

5F → Adaptation  → vehicle configuration → Apple DIO → enable CarPlay

5F → Adaptation  → vehicle configuration → Google GAL → enable Android Auto 
