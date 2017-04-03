# Resize_SD_image
A linux bash-script for taking an image of an SD card and shrinking it to the actual space used on the SDcard

# Dependencies    
The package "dcfldd" needs to be installed in order for the script to function.

# Usage
To use this script, plug in an sdcard to a linux based computer. and run the command as superuser, passing it two arguments. Device to read, and the image file to save as.

Example

    sudo ./resizeimg /dev/mmcblk0 /home/$USER/test.img
    
Video explaining the script: https://www.youtube.com/watch?v=9FokMQYKnik
[![Video explaining the script: https://www.youtube.com/watch?v=9FokMQYKnik](https://img.youtube.com/vi/9FokMQYKnik/0.jpg)](https://www.youtube.com/watch?v=9FokMQYKnik)

# Attribution
This script would not have been possible without the great article at http://www.aoakley.com/articles/2015-10-09-resizing-sd-images.php

I also just found out the author of that article made a script a month ago. however mine is simpler, and provides more general support.
