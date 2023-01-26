# LCD2USB #

**[LCD2USB][1]** -- (c) 2005-2007 by Till Harbaum 


## Description ##

**[LCD2USB][1]** is a simple and cheap HD44780 LCD to USB interface.
This interface is currently supported by the [lcd4linux][2] project.

Since version x.07, `lcd2usb` supports a second avr usb stack.
The verson numbering is `1.xx` for the **avrusb** version and
`2.xx` for the **usbtiny** version. Both versions provide identical
functionality. 


### avrusb version ###

The firmware code itself is distributed under the GPL, but
the usb code comes under a separate license.

Please see the `.txt` files in `usbdrv` for details.


### usbtiny version ###

The **usbtiny** stack comes under the regular GPL. If you want
to derive further projects from **lcd2usb** and want to stay
under the regular GPL you can just remove the **avrusb** specific
files.


[1]:	<http://www.harbaum.org/till/lcd2usb>
[2]:	<http://ssl.bulix.org/projects/lcd4linux/wiki/WikiStart>
