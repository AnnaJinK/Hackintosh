# Hackintosh
This EFI setting is for the following systems  
You can modify it with your SMBIOS.
	
 Main Monitor resolution : 2560x1440 (75Hz)  
 Clover GUI resolution : 2560x1440  
 Theme : Alita  
 DVI-D cable used  

 **OS** : High Sierra 10.13.6 (17G65)  
 **Monitor** : Viewsys QHD(75Hz), BenQ FHD(60Hz)  
 **CPU** : Intel i7-8700 3.2Ghz (6C/12T)  
 **M/B** : B360M AORUS GAMING 3  
 **GPU** : GTX960 2GB  
 **CNVi** : AC-9560 (wifi does not work but b/t is work.)  
 **RAM** : 16 GB  
 **NVME** : Colorful 240GB  
 **SSD** : Crucial M550 128GB  
 **HDD** : Seagate 2TB, Toshiba 500GB 
   
  

# Update
### 2019-02-10 Sun
If you are using a DVI-D (dual-link) cable and want to use QHD resolution or higher with the Clover GUI, disable CSM in your motherboard BIOS settings. 
#### What is the CSM?
The CSM is a component of the UEFI firmware that provides legacy BIOS compatibility by emulating a BIOS environment.  
If you do not use the legacy boot process, you can disable it and use only the UEFI BIOS boot process.

### 2019-02-16 Fri
Temperature, fan speed kext added  
#### Optane memory
macOS does not support Optane memory.  
If your system has **Optane memory** installed and you do not want to remove it, just add **nvme = -1** to Boot arg.  
But, this option also disables other nvme devices.


# Credits
Changes were made by Heejoong Kim (2019) 
