# GreysESOReshadePreset
I worked on a light-weight, high performant yet beautiful ESO reshade preset.

## How to install (if you don't have Reshade)
0. Top-right click on the Code button - then Download ZIP
1. Extract and choose the desired folder (I suggest use the current Reshade version 5.9.2)
2. Go to your ESO installation folder. (Usually something like C:\Program Files (x86)\Steam\steamapps\common\Zenimax Online\The Elder Scrolls Online\game\client)
3. Make sure to remove any remnants of existing reshade installation (Make a backup). If you are not sure which files are relevant, check this link: https://reshade.me/forum/general-discussion/4398-howto-uninstall-reshade
4. Copy the following files and folders to your games client folder:  
   - [reshade-shaders]  
   - dxgi.dll  
   - ReShade.ini  
   - Grey.ini  
6. Start the game
7. Open reshade by pressing POS1 / F2
8. Check if all effects have been loaded correctly and have a checkmark
9. Set Performance mode in the bottom right
10. Close menu and enjoy

*Note: * To open the reshade menu, press pos1

## How to use (if you already have ReShade 5.9.2)
1. Load the Grey.ini into your games client folder
2. Start the game
3. open ReShade window and select Grey.ini preset
4. enjoy

## Effects in use
1. PD80LUT - using a color table I changed the colors of the game to change the overall very purple-ish shadow tint and make the colors pop more and more natural
2. AmbientLight- Adds a soft glow to certain illuminated areas without interfering with your map or other UI views.
3. LocalLaplacian - Gives clarity and contrast
4. LumaSharpen - Gives the image and textures way more clarity and sharpness
5. Lightroom - change color and exposure
6. EyeAdaption - Makes sure highlights and shadows never get too strong
