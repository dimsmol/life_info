## Paper

- [AllTrails](https://www.alltrails.com/) is good for printing
  - print at FedEx or [spinnprint](https://www.spinnprint.com/)
  - use [waterproof paper](https://www.rei.com/product/896272/)

## For GPS

- Garmin topo maps aren't good, don't buy them
- use [OSM](https://wiki.openstreetmap.org/wiki/OSM_Map_On_Garmin) instead:
  - [USA OSM Topo Routable](http://www.gmaptool.eu/en/content/usa-osm-topo-routable)
    - can be installed on SD card with [MapManager / MapInstall](https://www8.garmin.com/support/agree.jsp?id=3825)
  - non-topo (not good for backpacking, but may be useful otherwise):
    - [Free maps for Garmin brand GPS devices](http://garmin.openstreetmap.nl)
      - can create `.img` that can be just copied to SD card
    - [OpenMapChest](https://www.openmapchest.org)

### moving files to GPS

Note:

- connecting GPS via USB allows to work with both GPS internal storage and installed SD card (if any)
- also, SD card can be used alone (with card reader)

This works with GPSMAP 64:

- maps
  - put your `.img` file into `Garmin/` folder on SD card
- GPX
  - put your GPX file into `Garmin/GPX/` folder on SD card
- what may work for other files:
  - connect GPS via USB
  - see where the files you need to add are on GPS
  - put your files under similar path on SD card

### free soft from Garmin

- [Basecamp](https://www.garmin.com/en-US/shop/downloads/basecamp)
  - work with routes, tracks, see them on map, upload to GPS, etc.
- [MapManager / MapInstall](https://www8.garmin.com/support/agree.jsp?id=3825)
  - create `.img` map file and put it to GPS or SD card
- [MapConverter](https://static.garmincdn.com/pumac/MapSource_MigratingGarminMapProductsfromWindowstoMacComputers.pdf)
  - presumably for converting maps for using on MacOS, but it looks like everything works without such conversion

### Linux

- [gmaptool](http://www.gmaptool.eu/en/content/gmaptool) can create `.img` files but I had no luck with it
  - using it on the files from `.gmap` folder downloaded from [USA OSM Topo Routable](http://www.gmaptool.eu/en/content/usa-osm-topo-routable) created `.img` file, but putting it to SD card had no effect (GPS couldn't detect it)
- `MapInstall` can potentially be used with `wine` but I had no luck with it
  - installation can be tricky
  - after installation it runs, but cannot detect connected device or SD card
  - and it doesn't allow just create `.img`, it requires connected device or SD card

misc links:

- [GPSBabel](https://www.gpsbabel.org) - tracks, etc.
  - `sudo apt-get install gpsbabel gpsbabel-gui`
  - [fixing USB permissions](https://www.gpsbabel.org/os/Linux_Hotplug.html#ubuntu)
- [USB Garmin on GNU/Linux](https://wiki.openstreetmap.org/wiki/USB_Garmin_on_GNU/Linux)
- [Run a Garmin GPS under Linux](http://www.gpspassion.com/forumsen/topic.asp?TOPIC_ID=121878)
- [Running Garmin MApSource with Wine](https://ubuntuforums.org/showthread.php?t=1483930)
