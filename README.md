### WrtSerial ###

Simple serial adapter for most of WRT-capable router boards. Following pinouts
are supported:

|  1  |  2  |  3  |  4  |
|:---:|:---:|:---:|:---:|
| VDD | TXD | RXD | GND |
| VDD | RXD | TXD | GND |
| GND | TXD | RXD | VDD |
| GND | RXD | TXD | VDD |


If nothing is received first time you plug it in, just rotate it around to
switch RXD/TXD lines.  Adapter will automatically adjust to voltage levels of
a destination board.
