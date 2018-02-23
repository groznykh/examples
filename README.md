# Waterlinked API examples

## About

Example applications using the Waterlinked Underwater GPS API. See http://waterlinked.com for more details.
The example applications are set up to use the Waterlinked Demo Server by default and should be changed
to the IP address/port of your kit. (For example: http://192.168.2.94)

### About nmeaoutput.py

Generate NMEA sentence from the global (lat, lon) and output it to either UDP or Serial port

### About getposition.py

Example of how to get both global (lat/lon) and relative position (x,y,z) from the Waterlinked Underwater GPS.

### About externaldepth.py

Example of how to send external depth data to the Waterlinked Underwater GPS. This is needed when
using the Locator A1 and is typically part of ROV integration

### About externalNMEA.py

Example of how to send external position data to the Waterlinked Underwater GPS. It reads NMEA messages from a device and parses it before sending it to the master electronics. 

### About tracklog.py

Example of how to store positions into a tracklog while the system is running into a [GPX file](https://en.wikipedia.org/wiki/GPS_Exchange_Format) for later viewing or processing.

## Requirements

* Python 2.7 (http://python.org)
* pip (https://pip.pypa.io/en/stable/installing/)

## Installation

Install the required Python packages

```
pip install -r requirements.txt
```

