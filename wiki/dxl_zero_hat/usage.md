# Usage
Assemble the shield on top of the Raspberry Pi. Connect the Dynamixel motor chain to the appropriate connector. Connect the proper power supply to the barrel jack connector. More information about choosing the proper power supply can be found on the specification page.

> ⚠ Warning: Do NOT connect the Raspberry Pi to a power source while the shield is powered! 

### Optional Expansions
- Reset Button:
  In order to use the reset button, wire the RUN & GND wires to their respective header on the Pi.


## Indicators
The shield contains a single RGB LED with the following indication flow:

🔴 **Red** - Shield main power connected

🔵 **Blue** - Raspberry Pi power connected

⚪ **Magenta** - _Constant_: power good, _3 blinks_: device ready, _continuos blinking_: searching for network


## Safety Instructions
To avoid malfunction or damage to this product please observe the following:

- Do not expose to water, moisture or place on a conductive surface whilst in operation.
- Do not expose it to heat from any source; Raspberry Pi 4 Model B is designed for reliable operation
at normal ambient room temperatures.
- Take care whilst handling to avoid mechanical or electrical damage to the printed circuit board
and connectors.
- Avoid handling the printed circuit board whilst it is powered and only handle by the edges to minimize the
risk of electrostatic discharge damage.