# Drivers for HP DeskJet Ink Advantage 5075

- Download latest `hplip-*.run` file for Elementary OS from [website](https://developers.hp.com/hp-linux-imaging-and-printing/gethplip)
- `$ chmod x+u hplip-*.run`
- `$ sudo hplip*.run`
```
# configure: error: cannot find libusb support
$ sudo apt-get install -y libusb-dev

# configure: error: cannot find python-devel support
$ sudo apt-get install python3.9-dev
```
- Restart laptop
- Connect printer to created mobile hotspot, laptop connect to the same mobile hotspot
- Run `$ sudo hp-setup`
