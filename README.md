# tek-p6860-adapter

This board is designed to take the Tektronix P6860 compression probe found on many Tektronix logic analyzers and break them out into 0.1" header. It includes a single 9-position SMD DIP switch so that you can individually choose to tie the grounds together to allow single-ended mode usage for the individual inputs. 

The Library folder contains a KiCad symbol and footprint for the probe pad layout.

The base schematic uses J-lead SMD DIP switches to save space, but there is an alternate set of gerber files for gull-wing lead DIP switches in the main directory. 

I've selected a set of wire-wrap style 0.1" header strips that go through the board, allowing you to use headers that have sockets as well as pins on the ones I've built myself. The Digi-Key part number for this is SAM1125-32-ND.

The matching gull-wing DIP switch part number is CT2199LPST-ND.
