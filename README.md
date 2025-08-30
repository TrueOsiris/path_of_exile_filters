# Path of Exile 1 & 2 - filters

Latest filter is compatible with Path of Exile 2 v0.3
Basic filters for path of exile

## Info
Place the .filter file in the "Path of Exile" map in My Games on Windows.<br>
The path should be something like C:\Users\youruser\Documents\My Games\Path of Exile\

### 1. Basic. Universal filter for every class.
This filter hides white and blue items unless they have max sockets with all connections

    
### 2. NeverSink's Indepth Loot Filter
Full credit to NeverSink. I copied this very elaborate filter here as a reference.


### 3. Stat requirement borders. Universal filter for every class.
Basic filter + border colors based on required stats. (Work in progress, always adding newly found items)

#### **hidden** items
- white and blue wearable items that
  - haven't got the maximum amount of sockets
    AND
  - haven't got all their sockets linked.
- white and blue rings without a socket.
- white and blue amulets, that aren't Onyx.
- white and blue quivers
- white and blue belts
- white flasks of types Utility, Life, Mana, Hybrid

#### Highlight Rare items that do not have max linked sockets
- 50% transparant background
- 50% transparent colored border (border color: see next point)
- slightly smaller font

#### Wearable items get borders
- border color dependent on stats required
  
| Stat requirements | Border color |
| ----------------- | ------------ |
| int               | ![#](https://placehold.co/12x12/0000FF/000000) dark blue |
| int > str         | ![#](https://placehold.co/12x12/7D00FF/000000) violet |
| int = str         | ![#](https://placehold.co/12x12/7D007D/000000) purple |
| int < str         | ![#](https://placehold.co/12x12/FF007D/000000) magenta / deep pink |
| str               | ![#](https://placehold.co/12x12/FF0000/000000) red |
| str > dex         | ![#](https://placehold.co/12x12/FF7D00/000000) vibrant orange |
| str = dex         | ![#](https://placehold.co/12x12/FFFF00/000000) yellow |
| str < dex         | ![#](https://placehold.co/12x12/7DFF00/000000) lime green |
| dex               | ![#](https://placehold.co/12x12/00FF00/000000) green |
| dex > int         | ![#](https://placehold.co/12x12/00FF7D/000000) teal |
| dex = int         | ![#](https://placehold.co/12x12/00FFFF/000000) cyan |
| dex < int         | ![#](https://placehold.co/12x12/007DFF/000000) azure |







#### Highlighted items on minimap
- all orbs get a purple triangle on the map

![filter 3 screenshot](img/3.path_of_exile_filter.png)

## Configuration

![Path of Exile options](img/PoEoptions.png)
