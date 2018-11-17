KPVBooklet for Kindle Touch, Kindle Paperwhite, New Kindle and Kindle Voyage
======================================

KPVBooklet is a Kindle booklet for starting KoReader/HackedUpReader
and updating last access and percentage finished information
in Kindle content catalog entry of the opened document. 

User can switch the open type in KUAL KPVBooklet extentions.

KPVBooklet is licensed under the MIT license. See the file
LICENSE for more details.

## building

- gather and install dependencies
  - getting kindle device jars
    - https://github.com/aerickson/kindle-jar-extractor
    - other methods (via ssh/usbnetwork?)
  - get other dependencies
    - OS X
      - `brew install gnu-tar libarchive ant`
    - linux/debian
      - not tested, but likely `apt install libarchive-dev ant`
- build and package
  - build the jar
    - `KINDLE_EBOOK=<DIR_WITH_DEVICE_JARS> ant`
  - package
    - `./build-updates.sh`