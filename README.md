# StarlinkEphemeris

This module allows you to download and parse Starlink ephemeris files.

## Setup

Simply add this module via `pip`

```
pip install starlink_files
```

## Using

You can:

- Download any available public files from SpaceTrack
- Parse Starlink ephemeris

### Downloading public files



### Parsing Starlink ephemeris

It's as simple as this:

```py
from spacetrack_files.files import EphemerisFile

eph = EphemerisFile('MEME_54190_STARLINK-5281_2210828_Operational_1375864140_UNCLASSIFIED.txt')
```

