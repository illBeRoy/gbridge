# gbridge
*MacOS and OSX bridge interface listing*

### what

on mac you can bridge internet connection to other devices using usb or thunderbolt outputs. use this tool in order to find out the ip of those bridged devices.

### why

found it easy to automate some scripts when bridging connection to my raspberry pi (easier to find the ip to ssh into, for instance).

### install

`pip install gbridge`

### usage

* `gbridge <interface name>` will print the ip of the given bridged interface, or nothing at all
* `gbridge --all` will print all bridged interfaces

### system requirements

macos \ osx.
