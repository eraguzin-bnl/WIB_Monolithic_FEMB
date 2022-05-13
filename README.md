# WIB_Monolithic_FEMB
In-progress files for getting the WIB to work with the monolithic FEMB

The 2 files outside of the /sw/ folder need to be put into /etc/rc5.d on the WIB, so that when it starts up, it can read the backplane and dynamically assign the IP, MAC and gateway addresses based on where it is.

Remember to just add the new updated gateway file. Don't know the logic behind it yet.
