# ES-theme-Insert-Rom-core-
INSERT ROM is a theme for EmulationStation (RetroPie version)
It was designed to display cool and attractive frontend for bartop but is as good for TV (but shouldn't be the best theme for smaller screens)
The theme is available both for 16:9 or 4:3 ratio screen and have three options:
	- Normal mode (wide video snaps)
	- Detailed mode
	- Detailed mode custom template


--------------------------------------------------------------------
1) Which theme version to use ?
2) How to install ?
3) Known issues
--------------------------------------------------------------------


1) Which theme version to use ?

If your are not interested by having a custom hardware template, so choose INSERT ROM CORE theme.
INSERT ROM CORE theme coutains all four default templates:
	- 16x9
	- 4x3
	- 16x9 detailed
	- 4x3 detailed
	
If you are interested by having a custom hardware template, so choose INSERT ROM DETAILED theme.
INSERT ROM DETAILED theme contains 16x9 version and a 4x3 mod to install in case of 4:3 ratio screen.


2) How to install ?

**For CORE version withe 16:9 ratio:**
	Simply upload core folder to /home/pi/.emulationstation/themes

**For CORE version withe 4:3 ratio:**
	Upload core folder to /home/pi/.emulationstation/themes
	Open theme.xml at the root folder with a text editor and
	change: <include>./_inc/templates/16x9.xml</include>
	by: <include>./_inc/templates/4x3.xml</include>

**For Detailed non-custom version 16:9 ratio :**
	Upload core folder to /home/pi/.emulationstation/themes
	Open theme.xml at the root folder with a text editor and
	change: <include>./_inc/templates/16x9.xml</include>
	by: <include>./_inc/templates/16x9_details.xml</include>

**For Detailed non-custom version 4:3 ratio :**
	Upload core folder to /home/pi/.emulationstation/themes
	Open theme.xml at the root folder with a text editor and
	change: <include>./_inc/templates/16x9.xml</include>
	by: <include>./_inc/templates/4x3_details.xml</include>

**For Detailed custom version 16:9 ratio :**
	Upload core folder to /home/pi/.emulationstation/themes
	then upload Mod custom detailed 16:9 to Insert Rom theme folder

**For Detailed non-custom version 4:3 ratio :**
	Upload core folder to /home/pi/.emulationstation/themes
	then upload Mod custom detailed 4:3 to Insert Rom theme folder
	
	
3) Known issues
Using OMX player don't permit for the moment to use zIndex properties. You have to disable the hardware renderer to make the theme works properly.

Detailed custom version can cause some lack of performance. You may improve the experience by increasing VRAM to 100 in EmulationStation options.
