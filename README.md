# Hackintosh
This EFI setting is for the following systems:
	
 Main Monitor resolution : 2560x1440 (75Hz)  
 Clover GUI resolution : 2560x1440  
 Theme : Alita  
 DVI-D cable used  
	
 **OS** : High Sierra 10.13.6 (17G65)  
 **CPU** : Intel i7-8700 3.2Ghz (6C/12T)  
 **M/B** : B360M AORUS GAMING 3  
 **GPU** : GTX960 2GB  
 **CNVi** : AC-9560 (wifi does not work but b/t is work.)  
 **RAM** : 16 GB  
 **NVME** : Colorful 240GB  
 **SSD** : Crucial M550 128GB  
 **HDD** : Seagate 2TB, Toshiba 500GB 


#### 2019-02-16 Fri
Temperature, fan speed kext added

If your system has **Optane memory** installed and you do not want to remove it, add **nvme = -1** to Boot arㅎ.  
But, this option also disables other nvme devices.
