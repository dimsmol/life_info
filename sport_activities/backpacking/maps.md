# Maps

## Paper

- [AllTrails](https://www.alltrails.com/) is good for printing
  - print at FedEx or [spinnprint](https://www.spinnprint.com/)
  - may want special paper:
    - [all-weather](https://www.rei.com/product/896270/rite-in-the-rain-all-weather-letter-copier-and-laser-paper)
    - [waterproof](https://www.rei.com/product/896272/rite-in-the-rain-duracopy-waterproof-copier-laser-paper-letter)

## GPS

- Garmin topo maps aren't good, don't buy them
- use [OSM](https://wiki.openstreetmap.org/wiki/OSM_Map_On_Garmin) instead:
  - [USA OSM Topo Routable](http://www.gmaptool.eu/en/content/usa-osm-topo-routable)
  - non-topo (not good for backpacking, but may be useful otherwise):
    - [Free maps for Garmin brand GPS devices](http://garmin.openstreetmap.nl)
      - can create `.img` that can be just copied to GPS SD card
    - [OpenMapChest](https://www.openmapchest.org)

### free soft from Garmin

- [Basecamp](https://www.garmin.com/en-US/shop/downloads/basecamp)
- [MapManager / MapInstall](https://www8.garmin.com/support/agree.jsp?id=3825)
- [MapConverter](https://static.garmincdn.com/pumac/MapSource_MigratingGarminMapProductsfromWindowstoMacComputers.pdf)

### using on Linux

Had no luck with combining `*.gmap` downloaded from [USA OSM Topo Routable](http://www.gmaptool.eu/en/content/usa-osm-topo-routable) with [gmaptool](http://www.gmaptool.eu/en/content/gmaptool) - copying resulting `.img` to `Garmin/gmapsupp.img` had no effect, while `.img` from [Free maps for Garmin brand GPS devices](http://garmin.openstreetmap.nl) worked ok.

misc links:

- [GPSBabel](https://www.gpsbabel.org) - tracks, etc.
  - `sudo apt-get install gpsbabel gpsbabel-gui`
  - [fixing USB permissions](https://www.gpsbabel.org/os/Linux_Hotplug.html#ubuntu)
- [USB Garmin on GNU/Linux](https://wiki.openstreetmap.org/wiki/USB_Garmin_on_GNU/Linux)
- [Run a Garmin GPS under Linux](http://www.gpspassion.com/forumsen/topic.asp?TOPIC_ID=121878)
- [Running Garmin MApSource with Wine](https://ubuntuforums.org/showthread.php?t=1483930)
