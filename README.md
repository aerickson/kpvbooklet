KPVBooklet for Kindle Touch, Kindle Paperwhite, New Kindle and Kindle Voyage
======================================

KPVBooklet is a Kindle booklet for starting KoReader/HackedUpReader
and updating last access and percentage finished information
in Kindle content catalog entry of the opened document. 

User can switch the open type in KUAL KPVBooklet extentions.

KPVBooklet is licensed under the MIT license. See the file
LICENSE for more details.

## building directions

1. getting kindle device jars

use https://github.com/aerickson/kindle-jar-extractor. copy the output somewhere on your computer.

1. get other dependencies

```
# install deps - OS X
brew install gnu-tar libarchive ant
# install deps - linux/debian
# TBD... `apt install libarchive-dev`?
```

1. build and package

```
# build JAR
export KINDLE_EBOOK=<JAR_EXTRACTOR_DIR>
ant

# package
./build-updates.sh
```