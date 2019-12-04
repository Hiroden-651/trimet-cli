# trimet-cli
Simple command line utility for getting TriMet schedules and arrival times based on transit stop ID.
## Overview
The trimet-cli utility displays transit information(schedules, alerts, etc) about the PDX area's(Portland Oregon) TriMet transit system by using a specific URL pattern to collect information from the ["trimet.org"](https://trimet.org/).
## Requirements
This utility is meant to be run in a UNIX-like environment and makes use ubiquitous utilities found in these environments such as curl, sed, and grep.
## Usage
This utility retrieves transit information which corresponds to specific stop IDs. 
* -A/-a/--alerts \[StopID\]: retrieve alerts for transit options corresponding to StopID number.
* -L/-l/--lines \[StopID\]: display all transit options corresponding to StopID number.
* -S/-s/--schedule \[StopID\]: display full schedule for all transit options corresponding to StopID number.
* --help: display help page showing all option usage.
## License
This project uses the MIT License.