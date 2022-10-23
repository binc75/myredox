# My REDOX
# Configurations and notes

## Configure
### Install QMK 
https://docs.qmk.fm/#/newbs
### Config files
Create a new directory layout in the `/home/nbianchi/qmk_firmware/keyboards/redox/keymaps` directory, 
for example
```
mkdir /home/nbianchi/qmk_firmware/keyboards/redox/keymaps/nbianchi
```
Create your own configs
```
config.h
keymap.c
readme.md
rules.mk
```
### Basic Keycodes
https://github.com/qmk/qmk_firmware/blob/master/docs/keycodes_basic.md


## Compile 
```
qmk compile --keyboard redox --keymap nbianchi
```

## Flash
```
qmk flash --keyboard redox --keymap nbianchi
```
