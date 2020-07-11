### U-boot
##### u-boot configurations
- Using C preprocessor to avoid the dead code.There are two classes for configuring 
  variables<br><br>
  `CONFIGURATION _OPTIONS_` : Selected by the user according to the need.<br>
  `CONFIGURATION _SETTINGS_`: Hardware dependent.<br>
  
- previously the configuration was done by editing and making symlink files 
  mannually. More recenly u-boot have added the kbuild infrastructure as in the linux.Now you can use the `make menuconfig` command to configure your build.
  
##### Selection of Processor Architecture and Board Type
- For all supported boards u-boot has ready to use default configuration available.
  just you have to do is `cd u-boot` `make <board_name>_defconfig`
  
- For all the supported boards you can visit ``.<br>
- For all the no longer supported boards you can visit `u-boot/doc/REDAME.scrapyard`<br>   
  
  
  
  
