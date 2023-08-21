# Tile Map Playground
This project is designed to develop a tilemap template with 45 and 1x2 slopes.

### Requirements
Godot `4.1`
Tiled `1.10.2`
Aseprite `1.3`

### Pixel Art
Related .asesprite files are found in `scratch/` directory.

### Level Design
Tiled project file is `playground.tiled-project`. Related project files are located in the `tilemap/` directory.
Create a map-XX.tmx file in this directory and add TileLayers `prototype`, and `terrain`.
Set the TileLayer property bool `noExport` on the `prototype` layer.
Add tilemaps `autotiles.tsx` and `template.tsx` from the `tiles/` directory.
Draw a prototype level using the the `autotiles` tilemap on the `prototype` layer.
Press `ctrl-M` to generate terrain output on the `terrain` layer.
Press `ctrl-E` to export to the `maps/` directory as a .tscn file.

### Game Engine
After exporting you can open the Godot editor and see TileMap objects in Godot.
