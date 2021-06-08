# qmk_config_crkbd
This is my personal config for Corne Keyboard (crkbd)



comands:

# CREATE A FOLDER OF KEYMAPS

#qmk new-keymap

# AFTER THAT YOU HACE TO COMPILE

qmk compile -kb crkbd -km jppalmab

# AFTER THAT BOOTLOADER THE QMK FIRMWARE

make crkbd/rev1:jppalmab:dfu
