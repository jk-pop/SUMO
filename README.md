# SUMO
Simulation of Urban Mobility Initial Playground Setup

```
This setup instructions are meant for users who are utilizing SUMO in Instant Veins.
The scripts are meant to save time for users who are beginning to play around with SUMO in the Veins platform.
Main purpose for this it to render OpenStreetMap to SUMO and create a simulation environment.
```
## Update and Find Version

* sudo apt update && upgrade

Finding out which version you are running

* uname -a

## Download and Setup

* git clone https://github.com/jk-pop/SUMO

Change directory to SUMO
* cd /SUMO

If you are running Debian 4.9.110, run:
* ./open-maps-4.7.sh

If you are running Debian 4.9.138, run:
* ./open-maps-5.0.sh
