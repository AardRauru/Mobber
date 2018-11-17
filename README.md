# Mobber

A mob database plugin for campaigns and global quests.

## Instructions

### Prerequisites

```
Mushclient version 5.06+
Aardmush r1916 snapshot+
```

### Installing

- [x] File -> Plugins -> Add -> Rauru_Mobber.xml
- [ ] File -> Plugins -> Add -> Rauru_Mobber_Miniwindow.xml (optional)

## New Installation Setup

A few commands are suggested to start on the right foot.

```
1. Enter 'mobber developer' to enable developer mode.
2. Enter 'mobber update areas' to add the default areas to mobber.
3. Enter 'mobber update rooms' to import your rooms from Aardwolf.db to mobber.
4. Enter 'mobber developer' to disable developer mode.
5. Enter 'mobber show areas' to verify areas and rooms were added.
6. Check 'mobber help' for all of the commands and to start logging mobs.
```

## Frequently Asked Questions

1. How do I upgrade to a new version of mobber?
   - Download the new version of mobber.
   - Drag and drop the mobber database and backups folder into the new version folder.
   - Delete the old folder.
   - Put the new version folder into your plugins folder.
   
2. Why are some mobs in cp/gq check different colors?
   - Red: The mob is currently dead.
   - Yellow: The area or room has not been logged.
   - Gray: The matching mob or room is outside of your level range.
   - Blue: A matching area was found.
   - Light Blue: A matching mob or room was found within your level range.

3. Why am I getting error prompts when trying to add a mob to a room?
   - You are likely trying to add a mob to a room or zone that you have not
     added to the mobber database yet.

## Developer Commands - Further Explained

1. mobber backup
   - Forces a manual backup of the database into /mobber/db_backups/
2. mobber vacuum
   - Defragments and frees up unused space from the database.
3. mobber remove zone
   - Removes the current zone and any rooms and mobs that belong to it.
     - Usually 'mobber removemob zone' command is sufficient enough.
4. mobber update keywords
   - Explicitly generates and adds mob keywords to the database.
     - This command must be used before manually assigning keywords.
     
# Author

* **Rauru** - *Plugin Author*

## Acknowledgments

* Anymouse - *Tester*
* Castiel  - *Tester*
* Crowley  - *Tester*
* Gizmmo   - *Tester*

![help](https://i.imgur.com/IywOEBw.png)
![menu1](https://i.imgur.com/AlbjeXo.png)
![menu2](https://i.imgur.com/GEf13X8.png)
![areas](https://i.imgur.com/VG0sAaZ.png)