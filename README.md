# PSKeeb 2

## Features

- Tenting design - good for your wrists, shoulders and back
- Stackable - portable
- 36 keys columnar layout - less movement when typing
- Trackpoint support

## Designs

- [pskeeb2 express](pskeeb2-express): All Kinds of switches, Blackpill controller, Diodeless, 9.2x9.2cm PCB
- [pskeeb2 cherry hotswap](pskeeb2-cherry-hotswap): Cherry MX Switch, Raspberry Pi Pico, Diodeless

## Assembly

#### Trackpoint

1. Follow [this great guide](https://github.com/alonswartz/trackpoint#q-how-do-i-identify-the-trackpoint-pinout) and [this topic](https://geekhack.org/index.php?topic=115912.0) to identify the trackpoint pinout
2. Solder GH cable to the trackpoint by refering to the socket wiring sequence: RST/DAT/CLK/GND/VCC (top to bottom)


## Developement

```
git clone https://github.com/klesh/pskeeb2.git
git submodule update --init --recursive
```

Use the following options when exporting gerber for JLCPCB manufactoring.
![gerber options for jlcpcb](kicad6-jlc-gerber-export-options.png)