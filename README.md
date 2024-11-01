# LSC Powerstrip Custom Firmware ESPHome
remove tuya and make it ESPHome


https://shop.action.com/en-nl/p/8712879159049/lsc-smart-connect-power-strip
 
https://github.com/v12345vtm/LSCPowerstripESPHome/blob/main/powerstrip_LSC_action.jpg

Chip : CB3S

flash : add a ttl serial to usb to rx1 tx1  , to create the first ESphome with bootloader use 
https://github.com/v12345vtm/LSCPowerstripESPHome/blob/main/2024_10_31_22_58_04_Window.png

to program LSC powerplug ( with energy monitor inside ) use https://github.com/wjtje/lsc-smart-connect-esphome
check also this manual : https://github.com/wjtje/lsc-smart-connect-esphome/blob/main/power-plug/README.md


u2f file , and flash it via "itchiptool"
info  to flash  : https://www.youtube.com/watch?v=t0o8nMbqOSA&lc=Ugwt_OvWiYub5lfB94d4AaABAg.AAGfQA1MczbAAGgyMCThEY

bootmode  : add a push button from CEN to GND and tap it to toggle the wifichip to bootmode

gpio14 = pin4 = relay a

gpio6  = pin7 = relay b

gpio7  = pin14 = relay c

gpio8  = pin13 = relay d

gpio23 = pin2 = led inside button

gpio10 = pin15 = button



