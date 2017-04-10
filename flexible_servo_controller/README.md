# Flexible Servo Controller

Flexible Servo Controller is, as its name suggests, a multi-use servo controller for brushed DC motors with incremental encoder feedback capable of driving motor currents of up to 25 A continuous (10 A continuous without active cooling) at supply voltages of up to 42 V (limited by an absolute maximum of 50 V).

The input position setpoint uses an encoder-like quadrature (A/B) interface and supports speeds up to 1 MHz. A configurable charge pump or active-low input activates the controller, bringing the output out of a configurable off state (brake or coast). Logic outputs are a controller active output, a fault output, and an encoder index output. A serial UART interface (RX/TX) allows for configuring and reading the system state with a command line interface which offers easy access to read and modify the system configuration, tune the controller parameters, read any logged system faults, and save settings to nonvolatile memory.

A programmer capable of programming devices over the PDI interface (such as an AVRISP MKII) and a serial terminal, such as a USB to UART converter (3.3/5 V compatible) are required to program and configure Flexible Servo Controller.

![Image](./img.jpg?raw=true)