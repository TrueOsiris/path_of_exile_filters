# Path of Exile - filters
Basic filters for path of exile

## Info
Place the .filter file in the "Path of Exile" map in My Games on Windows.<br>
The path should be something like C:\Users\youruser\Documents\My Games\Path of Exile\

### 1. Basic
This filter hides white and blue items unless they have max sockets with all connections

    
### 2. NeverSink's Indepth Loot Filter
Full credit to NeverSink. This very elaborate filter is here as a reference.


### 3. Stat requirement borders.
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
- slightly transparant background
- slightly transparent colored border (border color: see next point)

#### Wearable items get borders
- border color dependent on stats required
  
| Stat requirements | color |
| ----------------- | ----- |
| int | blue borders |
| int = str | purple borders |
| str | red borders |

#### Highlighted items on minimap
- all orbs get a purple triangle on the map


## Configuration

![Path of Exile options](img/PoEoptions.png)
