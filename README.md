# Readme
Hackintosh guide for Asus z390 p Catalina
Hackintosh for a newbie like me, I take 3 days to by pass this step so I think it is helpful for you

### My Hardwares
* Mainboard Asus Z390P
* G Skill Trident Z 32 GB
* Intel Core i7 9700K
* MSI RX580 Amor 8GB
* SSD Curical P1.
* Power Supply Corsair 650W
* Case cooler master
* Cooler AIGO ICY T120 (RGB)

### Requirements:
* USB (16GB or 32GB)
* Some Mac devices (like an Macbook pro, Macbook Air or use Virtual machine run MacOS).We will need it to run some patch (DSDT, ACPI), and create MacOS installer USB

### Fighting
* Create a USB installer: https://www.tonymacx86.com/threads/unibeast-install-macos-catalina-on-any-supported-intel-based-pc.285366/
* Use Clover Editor to add this Patch for Asus Z390 P
```
Comment: ACPI Patch
Find: A00A9353 54415301
Replace: A00A910A FF0BFFFF
```
If you don't do that, You will get a bug nvme assert error ...
* Patch DSDT
When you in Clover boot screen, you press F4 to genegrate a original DSDT, It will be located in: EFI/Clover/
... tobe continue
### Relavants: 
* Tonymac:
* Hackintosher
Clover: You can download it and use, maybe you must patch DSDT to use this clover.
