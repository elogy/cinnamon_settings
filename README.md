# cinnamon_settings
This repository includes my Cinnamon settings. Included is the `.cinnamon` folder, the `.themes` folder as well as a `dconf` dump.
Spices and applets are listed via their UUID, so they can be easily found ad the Cinnamon spices database.

## Installed Spices
- batterymonitor@pdfcurtis
- WindowListGroup@jake.phy@gmail.com


## Installed Applets
- temperature@fevimu
- sound-with-apps-volume@koutch

## Theme
|Feature|Theme|
|--|
|Window Decorations|Greybird|
|Icons|elementary-xfce-dark|
|Cursor|DMZ black|

### Desktop Theme
- Tyr Himinn (slightly modified)


### dconf dump
All other settings (at least those I could find) are included in the file `cinnamon_settings.dconf`.
This file can be restored via the shell:

```bash
dconf load /org/cinnamon/ < cinnamon_settings.dconf
```

Make sure you restart your Cinnamon session after the import, otherwise Cinnamon might crash.
