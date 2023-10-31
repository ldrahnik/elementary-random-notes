# Search in terminal history

You can use history | grep [search term] to show history that includes the term, or if you want to go through the matching history one at a time (skipping duplicates) you can use ctrl+r, enter the start of the command, and press ctrl+r repeatedly to go back though the results.

*(credits https://github.com/elementary/terminal/issues/277#issuecomment-456212222)*

# Error during updating with AppCenter
 
```
Aborted due to failure (Error pulling from repo: While pulling runtime/io.elementary.Platform/x86_64/7.2 from remote appcenter: Validating dirtree 6e340b9cffb37a989ca544e6bb780a2c78901d3fb33738768511a30617afa01d (/files/etc/debuginfod/): Dir 0 in dirtree: Invalid NULL filename)
```
 
- Solution
 
```
$ sudo flatpak --system repair
```
 
# Create new terminal tab with the same working directory as previous one
 
- double click on already opened terminal tab 
 
# Create new terminal tab with working directory
 
```
io.elementary.terminal -t --working-directory=$HOME/projects/..
```
 
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
