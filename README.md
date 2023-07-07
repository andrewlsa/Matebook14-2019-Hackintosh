Matebook 14 2019 Linux OpenCore EFI 

i5 8265U  
Intel Wireless AC9560   

macOS Sonoma 14.0 Beta (23A5286g)    
        
Thanks to    
Apple's macOS    
<a href="https://github.com/acidanthera">Acidanthera</a>'s <a href="https://github.com/acidanthera/OpenCorePkg">OpenCore</a>    
    
1. 去除触摸板补丁，感谢🦇<a href="https://github.com/williambj1">@bat.bat</a><img src="https://user-images.githubusercontent.com/63772067/133380601-420c0250-675e-4b88-b62c-86f44d6c8b02.jpeg" height="20" width="20"></img>  
2. 精简WiFi和蓝牙驱动，只保留AC9560固件, 精简AppleALC，仅保留ALC256。感谢<a href="https://github.com/zxystd">
@zxystd</a><img src="https://user-images.githubusercontent.com/63772067/133381457-70b04cf0-2c89-47c2-a1ce-6ddbd315d1c8.png" height="20" width="20"></img>的<a href="https://github.com/OpenIntelWireless/itlwm">OpenIntelWireless/itlwm</a>项目。     
3. 合并ACPI里面的SSDT。  
4. 去除config中不启用的选项，无用的.efi驱动和主题文件夹。  
5.     
    
HiDPI:  
将DisplayVendorID-dae和Icons.plist两个文件放入以下路径（macOS 11后需要新建）  
Big Sur ～ Ventura: /Library/Displays/Contents/Resources/Overrides  
Catalina: /System/Library/Displays/Contents/Resources/Overrides  
已开四个分辨率：1620x1080, 1512x1008, 1440x960, 1080x720。其它分辨率请自行修改。  
  



# Matebook-14-2019-Hackintosh
