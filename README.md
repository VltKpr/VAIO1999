# VAIO1999
Updated version of the Vaio 1999 active desktop wallpaper set

Clone the files in this repository to C:\Windows\Web\Wallpaper
Use a tool like rocksdanister's Lively Wallpaper to set as your desktop wallpaper.
*Note you will need to adjust the settings in lively to use WebView2 as the html player under Settings > Wallpaper > Plugins. This will require you to download additional files into the lively plugins folder and install the Windows Desktop runtime package from Microsoft.

The wallpapers have been upscaled using an AI tool to make them a resolution of 4000x3000. The upscaling isn't perfect, as the text in the top right corner is supposed to have a soft focus as intended by the original artist.
This code is also twice as long as it really needs to be. It's essientially a combination of the original code from Sony's Wallpaper set with other resolutions and bit depths in mind (even though bit depth is not an issue on today's machines, as all are 32 bit color) and updating it to a modern HTML5 format. 
I wanted to preserve the original file naming structure and decided to go that way instead of having a simple array and if-then loop for wallpaper 1.png, 2.png, etc. based on the hour.
