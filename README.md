
-Rename uvMaps Script:
Renames the UVmaps of all selected objects to UVMap.  This is done in order for objects to be joined without one loosing their UV map.

-Remove duplicated materials Script:
When importing models into a scene, materials that are already present get assigned a different number(redstone.dds becomes redstone.dds_001).
This script removes these duplicates.

-Item Renaming Script:	
This script should be run in your scene before exporting your complexes from blender.
It assigns a unique name to each item, which gives IWTE the needed context in order to understand if an item is a deteriorated version of another.
