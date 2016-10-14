# 55_unhookables
Redrawn and revised unhookable tileset for Teeworlds.

<img src=http://i.imgur.com/xrHSDOe.png>

This tileset was intended to look like an intermediary of the 0.6 and 0.7 versions of generic_unhookable, though it also includes several additional tiles (4x4, 1x2, 1.5x1) and colors (grey and light). Sources of the images as Inkscape SVGs are provided, along with automappers for each.

**Using the Tilesets Provided**
  - Navigate to the data/mapres/ folder inside your Teeworlds client directory
  - Download the images from the [PNG](/PNG) folder from this repo into the mapres folder
  - Navigate to the data/editor folder inside your Teeworlds client directory
  - Download the the \*.rules files from the [AUTOMAPPER](/AUTOMAPPER/) folder from this repo into the editor folder
  
**Editing the Tilesets Provided**
  - Editing of these tilesets can be done through the [SVG](/SVG/) files provided
  - Editing of these SVG files can be done using [Inkscape](https://inkscape.org/)
  - Once the SVG files are opened in Inkscape, you can utilize the layers provided by going to "Layers -> Layers..." in the menus or simply pressing CTRL + SHIFT + L
  - Once your have finished editing the tiles in Inkscape, you can export it as a PNG by going to "File -> Export PNG Image..." or simply pressing CTRL + SHIFT + E
  - Before you can use the exported PNG image as a tileset in Teeworlds, you must first apply some scripts to the file. These scripts can be downloaded here: https://ddnet.tw/downloads/ under the "Other Downloads" section as "Mapping Graphics Tools"
  - Once the scripts are downloaded, apply "dilate," "tileset_borderfix," and "tileset_borderadd" to the exported PNG image in that order
  - Place the image in the data/mapres/ folder in your Teeworlds client directory
  - If you need an automapper for that tileset, remember to rename the automapper rules file in the data/editor folder so that it has the same name as the PNG image

**Additional links:**
  - Teeworlds - https://www.teeworlds.com/
  - DDNet - https://ddnet.tw/
