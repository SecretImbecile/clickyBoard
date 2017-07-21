# clickyBoard
A Raspberry Pi add-on board that adds a simple switch and LED circuit for GPIO programming, using mechanical keyboard switches

Read the [documentation file](Documentation/clickyBoard.pdf).

![clickyBoard PCB render](render.jpg)

## FAQ

### What does clickyBoard add to my Pi?

clickyBoard adds a simple circuit to your Raspberry Pi for GPIO programming, featuring four input switches, as well as LED backlighting which can be controlled with a single output.

The board uses Cherry MX compatible switches, which are popular keyboard switches, that are widely and cheaply available along with compatible keycaps.

### Is this a HAT?

Not quite. The Raspberry Pi HAT [specification](https://github.com/raspberrypi/hats) requires a HAT to have an ID EEPROM. To keep this add-on board simple to assemble, this has been ommited. The clickyboard does adhere to the HAT mechanical specifications.
