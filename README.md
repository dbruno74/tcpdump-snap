# tcpdump-snap
A snap package for tcpdump/libpcap

## Install

To install the snap from the store use:

`sudo snap install tcpdump-snap`

To run tcpdump with -i <interface> option please run

`sudo snap connect tcpdump-snap:network-control`

after install.

To run tcpdump without -i <interface> option please run

`sudo snap connect tcpdump-snap:network-control`

`sudo snap connect tcpdump-snap:hardware-observe`

`sudo snap connect tcpdump-snap:firewall-control`

after install.

## Run
To run tcpdump:

`sudo tcpdump-snap.tcpdump <options>`
  
## Building

Simply clone this tree and call `snapcraft` in the toplevel dir

