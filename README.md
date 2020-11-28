matrigato's build of dwmstatus
============================

dwmstatus
------------
Barebone status monitor with basic functions written in C. This follows the suckless philosophy, to give you an easy way to extend the source code to your needs. It can be used as a [status monitor](https://dwm.suckless.org/status_monitor/) for dwm. See the helper functions for C [here](https://dwm.suckless.org/status_monitor/), to extend it to your needs. Just check it out and keep on hacking.


Installation
------------
Enter the following commands to build and install dwmstatus (if
necessary as root):

	make
	make install

Then add `dwmstatus 2>&1 >/dev/null &` to your .xinitrc


Configuration
-------------
The configuration of dwmstatus is done by editing and (re)compiling the source code.


License
------------
In jurisdictions that recognize copyright laws, the following licenses apply:

[dwmstatus](https://git.suckless.org/dwmstatus/) is available under the [MIT/X Consortium License](LICENSES/MIT).

Everything made by me is under [The Unlicense](LICENSES/UNLICENSE).