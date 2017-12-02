# Display Modpack

_For changes in this fork please look further below._

This modpack provides mods with dynamic display. Mods are :

- **display_lib**: A library for adding display entities to nodes;
- **font_lib**: A library for displaying fonts on entities;
- **ontime_clocks**: A mod providing clocks which display the ingame time;
- **signs**: A mod providing signs and direction signs displaying text;
- **signs_road**: A mod providing road signs displaying text;
- **steles**: A mod providing stone steles with text;

For more information, see the [forum topic](https://forum.minetest.net/viewtopic.php?f=11&t=13563) at the Minetest forums.

## Changelog

### 2017-12-02 Fork

- Added support for Unicode characters (limited to Unicode Plane 0: 0000-FFFF, see [Wikipedia](https://en.wikipedia.org/wiki/Unicode); Warning: all textures have changed names! Textures from original repository are not compatible!
- Added new, more readable character textures for languages: Western European, Eastern European (incl. Polish), Cyrillic, Turkish, Greek. Fonts used: [Grixel Kyrou 7 Wide](https://www.dafont.com/grixel-kyrou-7-wide.font) by Nikos Giannakopoulos (CC BY-ND), [Pokemon Classic](https://www.dafont.com/pokemon-classic.font) by TheLouster115, credits to Sarial84 on DeviantART for the Cyrillic alphabet (CC BY-NC-SA).
- Added a Bash script to generate any characters from any font.

### 2017-08-26

- Changed signs from wallmounted to facedir to improve textures and make it possible to use screwdriver. 
**IMPORTANT** : Map will be updated to change to new nodes but inventory items will turn into "Unknown items" and have to be re-crafted.

- Intllib support added with french translation (whole modpack, thanks to fat115) ;

- Punch on nodes to update entity (signs, signs_road and steles). Usefull in case of /clearobjects ;

- Changed wooden direction sign textures (signs) ;

- Added back and side textures to all signs (road_signs) ;

- Added more sign types : White/yellow/green signs and direction signs (signs_road) ;



