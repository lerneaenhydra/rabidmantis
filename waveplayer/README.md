# Waveplayer

Waveplayer is a general-purpose, standalone, stereo audio playback board. Wave files are read from a removable microSD or microSDHC card (up to 32GiB) with a FAT12/FAT16/FAT32 file system. Files with any combination of mono or stereo, 8-bit or 16-bit, and 8/11.025/16/22.05/32/44.1/48kHz sample rates are supported.

Waveplayer's analog output has an SNR level exceeding 90dB at full output amplitude and an estimated THD typically under 0.005% (3.9Vpp, 1kHz). A low-power mode allows for battery powered applications, with an idle-state current draw of typically 1.7 mA.

Six user-configurable inputs are available for triggering events (play, pause, next track, etc) on a rising or falling flank. One of these inputs can be used as an analog input for controlling the playback amplitude from -100dB to 0dB with a linear change in voltage.

A header row allows for directly connecting Waveplayer to a Cheapamp board (another rabidmantis OSHW project), for a complete audio amplifier system.

An integrated serial interface can be used for more complex control and allows for navigating the file-system, controlling the playback state, and changing system settings.

![Image](./img.jpg?raw=true)