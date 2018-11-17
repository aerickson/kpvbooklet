KPVBooklet for Kindle Touch, Kindle Paperwhite, New Kindle and Kindle Voyage
======================================

KPVBooklet is a Kindle booklet for starting KoReader/HackedUpReader
and updating last access and percentage finished information
in Kindle content catalog entry of the opened document. 

User can switch the open type in KUAL KPVBooklet extentions.

KPVBooklet is licensed under the MIT license. See the file
LICENSE for more details.

## building directions

1. getting kindle jars dependency

https://wiki.mobileread.com/wiki/Kindlet_Developer_HowTo#What_do_I_need_to_do_to_start_developing_Kindlets.3F

- ssh via usbnetwork: google
- kindle library extractor: http://cowlark.com/kindle/getting-started.html

1. get libraries

```
# install deps - OS X
brew install gnu-tar libarchive ant
# install deps - linux/debian
# TBD... `apt install libarchive-dev`?
```

1. build and package

```
# build JAR
ant

# package
./build-updates.sh
```