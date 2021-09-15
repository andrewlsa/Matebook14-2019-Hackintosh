Matebook 14 2019 Linux OpenCore EFI 0.7.2 

i5 8265U  
Intel Wireless AC9560   
WD SN720 512G  

Monterey B6，OC074   
1. 去除触摸板补丁，感谢<a href="https://github.com/williambj1">@bat.bat</a>  
2. 去除config中不启用的选项，无用的.efi驱动和主题文件夹。  
3. 合并ACPI里面的SSDT。  
4. 精简WiFi和蓝牙驱动，只保留AC9560固件。感谢@zxystd     
5. 想到再说。  
  
  
HiDPI:  
将DisplayVendorID-dae和Icons.plist两个文件放入  
Big Sur: /Library/Displays/Contents/Resources/Overrides  
Catalina: /System/Library/Displays/Contents/Resources/Overrides  
已开四个分辨率：1620x1080, 1440x960, 1280x854, 1080x720。其它分辨率请自行修改。  
  



# Matebook-14-2019-Hackintosh
