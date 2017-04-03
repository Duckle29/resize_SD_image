# Resize_SD_image
A linux bash-script for taking an image of an SD card and shrinking it to the actual space used on the SDcard

# Usage
To use this script, plug in an sdcard to a linux based computer. and run the command as superuser, passing it two arguments. Device to read, and the image file to save as.

Example

    sudo ./resizeimg /dev/mmcblk0 /home/mikkel/test.img
    
