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
| int               | <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"><rect width="12" height="12" fill="#0000FF"/></svg> dark blue |
| int > str         | <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"><rect width="12" height="12" fill="#7D00FF"/></svg> violet |
| int = str         | <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"><rect width="12" height="12" fill="#7D007D"/></svg> purple |
| int < str         | <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"><rect width="12" height="12" fill="#FF007D"/></svg> magenta / deep pink |
| str               | <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"><rect width="12" height="12" fill="#FF0000"/></svg> red |
| str > dex         | <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"><rect width="12" height="12" fill="#FF7D00"/></svg> vibrant orange |
| str = dex         | <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"><rect width="12" height="12" fill="#FFFF00"/></svg> yellow |
| str < dex         | <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"><rect width="12" height="12" fill="#7DFF00"/></svg> lime green |
| dex               | <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"><rect width="12" height="12" fill="#00FF00"/></svg> green |
| dex > int         | <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"><rect width="12" height="12" fill="#00FF7D"/></svg> teal |
| dex = int         | <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"><rect width="12" height="12" fill="#00FFFF"/></svg> cyan |
| dex < int         | <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"><rect width="12" height="12" fill="#007DFF"/></svg> azure |





#### Highlighted items on minimap
- all orbs get a purple triangle on the map

![filter 3 screenshot](img/3.path_of_exile_filter.png)

## Configuration

![Path of Exile options](img/PoEoptions.png)
