# Important 

That's outdated and not maintained fork of original project wrote by [Neil Horman](https://github.com/nhorman) which can be found [here](https://github.com/nhorman/dropwatch)

# What is Dropwatch?

This tool will show place where kernel drops/discards UDP packets.

## Example screen:

![Screen example](/drop_watch_screen.jpg)

# How to build on Ubuntu 14.04?

## Dependencies

First of all you need to have CONFIG_NET_DROP_MONITOR enabled in your kernel https://github.com/pavel-odintsov/drop_watch/wiki/Ubuntu-14.04-LTS-kernel-with-drop_monitor-support 

## Install dependencies:
```sudo apt-get install -y libnl-3-dev libnl-genl-3-dev binutils-dev libreadline6-dev```

Then clone repo, cd to src folder and run make.

And finally run tool:
```./dropwatch -l kas```
