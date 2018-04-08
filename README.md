# Keyboard mappings for using a Mac keyboard with Ubuntu

These are files for keyboard mappings, based on an English UK Mac keyboard, to work with Ubuntu. Fn and Backspace will give the delete behaviour. Essentially, this allows an English UK MacBook to run Ubuntu on a VM and continue typing without, mostly, any real difference in behaviour. Command replaces Control so CMD & S will save a file for example.

Place the ubm file into 

* /usr/share/X11/xkb/symbols

and add the evdev.xml snippet to inside the closing </layoutList> tag inside the evdev.xml file at

* /usr/share/X11/xkb/rules/