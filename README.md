# 55_unhookables
Redrawn and revised unhookable tileset for Teeworlds.

<img src=http://i.imgur.com/xrHSDOe.png>

This tileset was intended to look like an intermediary between the 0.6 and 0.7 versions of generic_unhookable, though it also includes several additional tiles (4x4, 1x2, 1.5x1) and colors (grey and light). Sources of the images as Inkscape SVGs are provided, along with automappers for each.

  - PNG tilesets should be placed in your client data/mapres/ directory.
  - Automapper rules should be placed in your client data/editor directory, with the same name as the tileset it corresponds to.
  - Inkscape SVGs may be used to edit the vector source of the tilesets
    - Inkscape site - www.inkscape.org
    - Use the layers provided to efficiently colorize the tiles (CTRL + SHIFT + L)
    - If you have edited and exported these tilesets, you must apply several scripts to the PNG for it to appear properly in Teeworlds. 
    - These scripts can be found here: www.ddnet.tw/downloads/ in the "Other Downloads" section.
    - Apply dilate, tileset_borderfix, and tileset_borderadd in that order to your exported images.

Additional links:
  - Teeworlds - www.teeworlds.com
  - DDNet - www.ddnet.tw
