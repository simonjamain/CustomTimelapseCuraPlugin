Enable to do awesome timelapse using a method similar to this video: https://www.youtube.com/watch?v=UqZ8Um5MZEA but without using octoprint !
I'll soon add a complete tutorial including the hardware (probably in french) for which I'll add the link here.

Here is a very short video of the results you can obtain from this script : https://www.youtube.com/watch?v=GuBmlGf-YKc

----------------

To add the script to your CURA here is the method:

*(copied from http://www.customize-3d.com/how-to-install-a-post-processing-script-for-postprocessingplugin-in-cura-3-2-1.html)*

How to Install a Post Processing Scripts in Cura (as of 3.2.1)

Find where your configuration folder is.

 1. Click Help menu item.
 2. Click "Show Configuration Folder".
 3. Find the folder call "scripts".
     If you don't see one create one in the configuration folder.
 4. Place the python script (with file extension .py) into the script folder.
 5. Restart Cura.

Now you should be able to see the newly added post processing script

 1. Click Extensions -> Post Processing -> Modify G-Code
 2. Click “Add a script”
 3. The newly added script name should appear in the dropdown list

----------------

**IMPORTANT NOTE:**
the display name of the script in cura is **Custom timelapse** and NOT Time lapse

**FUTURE IMPROVEMENTS:**
we should not try to reposition the head on the last layer

**WARNING:**
the default g-code is good for the creality ender 3 printer, don't forget to adjust your g-code according to your setup !

----------------

**CHANGELOG**

*2020-07-28* : fixed stringing phenomenon and added features like the photo trigger command (which and never used) and the display of the current picture number AND added a changelog ^^

*2020-11-28* : moved to a proper repo and added custom return speed capability