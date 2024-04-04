# Picasa ini parser

Updating this to python3, and changing output to a sqlite database instead of directly editing the photos.

This is intended to help change from organizing your photos in Picasa to another software like ShotWell. Since Picasa does not write metadata like the star rating and album belonging to the file itself, the information is not visible to other software. pictureparser will recursively parse picasa.ini files in your photo collection and write the album and star metadata an sqllite database.  You can then move them to the IPTC keywords field. Shotwell then recognizes and groups the photo like they were tagged.

__Developed on Python 3.9 and testing on Windows 10 with Picasa 3.9.1.4.1.__
__Please make a backup of your photos before copying the tags to them and use at your own risk!__

PIP Dependencies:
  - [configparser](<https://pypi.python.org/pypi/configparser> )
  - [IPTCinfo](https://pypi.python.org/pypi/IPTCInfo/)

### Usage:
Run pictureparser.py from your IDE
