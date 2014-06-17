# Global Cloudmap Repo

This repo serves as a distribution point for near realtime and archive access to global cloudmaps you can use with xplanet (see  https://github.com/chron0/xfce-planet) or as blender textures. Full pull not recommended :)


## Usage

### Latest near realtime cloudmap

You can simply get the latest image from:

    https://raw.githubusercontent.com/apollo-ng/cloudmap/master/global.jpg

### Cloudmap archive

To get archived images, just check out the specific commit(s) for the timestamp(s) you're interested in.

## Operation

![HOWTO make near realtime cloudmaps of our world yourself](https://raw.githubusercontent.com/apollo-ng/cloudmap/master/howto_global_cloudmap.jpg "HOWTO make near realtime cloudmaps of our world yourself")

The whole process is set up to work completely autonomously, pulling the latest images from
the following satellites, to get full planet coverage (except polar regions)

### Source Birds

  * MTSAT2 - Himawari 7 - L: 2006/02/18 - P: GEO E145°
    * Channel 4: 6.5-7.0um water vapor channel (IR3) with a HgCdTe detector

  * MSG3 - Meteosat-10 - L: 2012/07/05 - P: GEO 0°
    * Channel 9: 9.80-11.80um Spinning Enhanced Visible and InfraRed (HgCdTe) Imager (SEVIRI)
    * https://directory.eoportal.org/web/eoportal/satellite-missions/m/meteosat-second-generation 

  * MET7 - Meteosat-7 (IODC) - L: 2006/12/05 - P: GEO E57.3°
    * Channel 2:  
    * http://www.wmo-sat.info/oscar/satellites/view/301
    * https://directory.eoportal.org/web/eoportal/satellite-missions/m/meteosat-first-generation

  * GOES13 - GOES-N - L: 2006/05/24 - P: GEO W75° 
    * Channel 4: IR Imager

  * GOES15 - GOES-P - L: 2010/03/04 - P: GEO W135°
    * Channel 4: IR Imager

### Source image distribution

  Dundee Satellite Receiving Station, Dundee University, UK
  http://www.sat.dundee.ac.uk/

### Software

  https://github.com/jmozmoz/cloudmap

### License

Since we all paid for construction & launch of those birds with our tax
money the images belong to everyone. The actual creative work of stitching
the images together is done by software, which cannot claim anything
because it has no rights. Therefore you can do whatever you want with
these images.

### Support

Created and operated by Apollo-NG Mobile Hackerspace
https://apollo.open-resource.org/


