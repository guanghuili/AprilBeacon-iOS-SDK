## 1.2.4 (Oct 22, 2014)
Features:

*  Support iPhone 5s, iPhone 6, iPhone 6 plus simulator build

## 1.2.3 (Oct 10, 2014)
Features:

*  iOS 8 support

## 1.2.2 (Sep 22, 2014)
Bug fixes:

*  Build error in xocde 5

## 1.2.1 (Sep 15, 2014)
Bug fixes:

*  Remove all beacons when start discover
*  Issue that can't remove custom filter name
  
## 1.2.0 (Sep 10, 2014)
Feature:

*  Return acceleration value of the accelerometer sensor

Optimize:

*  Merge connection callback method to one

Bug fixes:

*  Can not get callback when beacon connected

## 1.1.7 (Sep 1, 2014)
Buf fixes:

*  Clean stored beacons when stop discovery

## 1.1.6 (Aug 26, 2014)
Buf fixes:

*  Can't callback when connected

## 1.1.5 (Aug 15, 2014)
Optimize:

*  Update sensor value more stable

## 1.1.4 (Aug 11, 2014)
Bug fixes:

*  Modify UUID failed in iOS8

## 1.1.3 (July 27, 2014)
Features:

*  Add  modelNumber property to ABBeacon

## 1.1.2 (July 23, 2014)
Bug fixes:

*  Multi callback when connected
*  Modify tx power failed 

## 1.1.1 (July 22, 2014)
Features:

*  Add firmwareRevision and manufacturerName property to ABBeacon
*  Add custom filter to ABBeaconManager. developer can find his own beacon with specified prefix name.
  
## 1.1.0 (July 3, 2014)
Features:

 *  Add sensor apis

 Bugfixes:

  *  Fix can't scan april beacons when connect to a beacon
  
## 1.0.3 (June 23, 2014)
Features:

 *  Support more April beacons
 
 Improvment
 
 *  Lazy alloc of object
 
 Bugfixes:

  *  Bug fix
  
## 1.0.2 (May 23, 2014)
Features:

 *  Change writeBeaconPassword method to authBeaconWithPassword
 
 Bugfixes:

  *  Read value crash on iOS 7.0
  *  Error handle of peripheral actions
 
## 1.0.1 (May 19, 2014)
Features:

 *  Add auth and reset beacon method to ABBeacon
 
## 1.0.0 (May 8, 2014)

Features:

*  Ranging and monitoring April beacons
*  Beacon connection support
*  Read/Write of Major, Minor, Power and Fequency