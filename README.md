# crestron-magicpacket

SIMPL# Pro class to power on devices using [Wake-on-LAN](https://en.wikipedia.org/wiki/Wake-on-LAN)


## Usage
```c#
WakeOnLAN WOL = new WakeOnLAN();
WOL.WakeUp(mac, broadcast);
```
Instantiate class and pass the mac address & broadcast address to the WakeUp method. 


## Contributing
Pull requests are welcome. 


## License
[GPL-3.0](https://choosealicense.com/licenses/gpl-3.0/)