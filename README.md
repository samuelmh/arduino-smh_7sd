# arduino-smh_7sd
An Arduino library to display text in a  seven segment display.


## Features

* Full basic alphabet [A-Za-z0-9].
* The time a character is shown is adjustable.
* Adjustable blink between characters.
* Configurable for common cathode or common anode 7 segment displays.
* Packaged as an Arduino library. With examples and syntax highlighting.
* It's also possible to make stroboscopic-like effects by changing the time the characters are being shown (1 ms) or not (7ms). If you move fast enough (with care, please) the display, you could draw at least 3 characters on the air.


## Video example
[![Video Example](https://img.youtube.com/vi/HGlXXlHXwxM/0.jpg)](https://www.youtube.com/watch?v=HGlXXlHXwxM)

### Components used in the example
* 1x arduino board.
* 1x prototype board.
* 1x seven segment display. (It's common anode type but the library allows controling a common cathode one as well.)
* 1x 330&#8486; resistor to the common anode.
* 9x cable. A cable for each segment connected to an arduino digital output and the cable that connects the common anode to the 5V.

### Disclaimer
Although I've used only one resistor connected to the common anode, this is not a good thing. The correct way will be connecting a 1K&#8486; resistor to each segment pin (8x 1K&#8486; resistors) so the voltage they use is always the same.

This decision was based on simplicity.

