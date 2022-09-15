# RP2040-Dev-Board
PCB Design(4 Layer) of Breadboard friendly RP2040 Dev Board with USB-C.
#### Layer:
Layer 1: Front Cu
Layer 2: Gnd
Layer 3: Gnd
Layer 4: Back Cu

Initially my designs had inner layers as gnd and 3.3V, I got some netlist parity when I uploaded to my PCB manufacturer. But KiCad was'nt showing any errors in DRC, So I made both layers as Gnd.
#### Manufacturing
All components were purchased in [lcsc.com](lcsc.com) except RP2040, Which I purchased locally for 80Rs(~$1)/μC from robu.in.

LCSC BOM: https://github.com/abhinav937/RP2040-Dev-Board/blob/main/RP2040_LCSC_BOM.csv

I got my PCBs manufactured from [Aisler](aisler.net). Board is yet to get assembled.

Rev2 has lot of inspiration from michael rangen's PCB layout. Also I've used KiBuzzard for silkscreen texts, Which I personally like very much.
