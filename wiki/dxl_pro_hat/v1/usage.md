# Usage
Assemble the shield on top of the Raspberry Pi. Connect the Dynamixel motor chain to the appropriate connector. Connect the proper power supply to the barrel jack connector. More information about choosing the proper power supply can be found on the specification page.

> ⚠ Warning: Do NOT connect the Raspberry Pi to a power source while the shield is powered! 

### Optional Expansions
- Reset Button:
  In order to use the reset button, wire the RUN & GND wires to their respective header on the Pi.
- CPU Fan: In order to add a CPU fan, connect it to the 3.3V/5V and GND header.


## Indicators
The shield contains 4 LED's:

🔴 **POWER** - Shield main power status

🔴 **PI** - Raspberry Pi power status

🔵 **COM** - communication activity status (constant: active, 3 blinks: device ready)

🔵 **NET** - Network activity status (constant: active, blinking: connecting)


## Safety Instructions
To avoid malfunction or damage to this product please observe the following:

- Do not expose to water, moisture or place on a conductive surface whilst in operation.
- Do not expose it to heat from any source; Raspberry Pi 4 Model B is designed for reliable operation
at normal ambient room temperatures.
- Take care whilst handling to avoid mechanical or electrical damage to the printed circuit board
and connectors.
- Avoid handling the printed circuit board whilst it is powered and only handle by the edges to minimize the
risk of electrostatic discharge damage.