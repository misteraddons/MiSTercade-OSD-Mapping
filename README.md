# MiSTercade OSD Combo Mappings
Add this ini updater below your main MiSTercade mapping database entryby editing the `downloader.ini` file at the root of the SD.

This repository contains a main mapping for MiSTercade V1 and V2 that has the OSD button combo set to down + start.

The OSD menu mappings in the main repositories don't have any OSD combo in them as some users have issues with accidentally activiating the menu.

## How to Integrate the Mappings into MiSTer Downloader:
To integrate it in a MiSTer device, add the following section to the end of to the file `downloader.ini` that should be placed at the root of the SD (if it doesn't exist, you may create it for this purpose).

MiSTercade V1 instructions:
```ini
[misteraddons/mistercade_v1_2025_freeplay_mappings]
db_url = https://raw.githubusercontent.com/misteraddons/mistercade_v1_2025_freeplay_mappings/db/db.json.zip

[misteraddons/mistercade_osd_mappings]
db_url = https://raw.githubusercontent.com/misteraddons/mistercade-osd-mapping/db/db.json.zip
```

MiSTercade V2 instructions:
```ini
[misteraddons/mistercade_v2_mappings]
db_url = https://raw.githubusercontent.com/misteraddons/mistercade_v2_mappings/db/db.json.zip

[misteraddons/mistercade_osd_mappings]
db_url = https://raw.githubusercontent.com/misteraddons/mistercade-osd-mapping/db/db.json.zip
```
After that, run *downloader* or *update_all* as usual. It will try to fetch the files from your newly created database. 
