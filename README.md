# RP2040-Dev-Board
PCB Design(4 Layer) of Breadboard friendly RP2040 Dev Board with USB-C. <br /> 
<img src="https://user-images.githubusercontent.com/79394309/195375858-6e62e76e-9350-4cd3-853a-cd9f15d12a3c.jpg" width="400">
#### Layer:

Layer 1: Front Cu <br /> 
Layer 2: Gnd <br /> 
Layer 3: Gnd <br /> 
Layer 4: Back Cu <br /> 

Initially my designs had inner layers as gnd and 3.3V, I got some netlist parity when I uploaded to my PCB manufacturer. But KiCad was'nt showing any errors in DRC, So I made both layers as Gnd.
#### Manufacturing
All components were purchased in [lcsc.com](lcsc.com) except RP2040, Which I purchased locally for 80Rs(~$1)/μC from robu.in. <br /> 

LCSC BOM: https://github.com/abhinav937/RP2040-Dev-Board/blob/main/RP2040_LCSC_BOM.csv <br /> 

I got my PCBs manufactured from [Aisler](aisler.net). <br /> 

Rev2 has lot of inspiration from michael rangen's PCB layout. Also I've used KiBuzzard for silkscreen texts, Which I personally like very much.
#### Refer my [documentation](documentation) for full information.
