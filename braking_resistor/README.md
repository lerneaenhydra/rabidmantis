# Braking resistor

Braking Resistor is, as it's name suggests, a general-purpose braking resistor primarily intended for handling regenerative power from low to mid-power servo and stepper-motor drives.

An external high-power shunt resistor is switched on, draining power from the bus when the bus voltage exceeds some limit V_{bus,high}, and kept on for at least t_{min} and until the bus voltage falls below V_{bus,low}.

Braking Resistor can be used with bus voltages ranging from 12 V to 75 V, and can sustain an average load of 8 A, or 35 A at a 5% duty cycle with 1 ms pulses, with the default pass transistor. Other transistor choices allow operation at up to 300 V and significantly higher currents.

![Image](./img.jpg?raw=true)