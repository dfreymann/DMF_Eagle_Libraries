## eagle-libraries 
Eagle component library files that I've modified or created. 


#### con_JST_XH_dmf.lbr 
---

JST-XH headers. Edited 4.10.15 dmf 
2 pin, 3 pin, 4 pin all should be OK

Original version (wrong hole sizes) from this fellow: 
"This libary is for adding JST-XH headers to you're project. It has pins 3-7. This is usefull for ballance connectors on lithium polymer batteries from 2-6 cells. The pin spacing was based on the datasheet that can be found here http://www.jst-mfg.com/product/pdf/eng/eXH.pdf" 
Source: http://www.rcgroups.com/forums/showthread.php?t=2304597

Corrected for XH 2/3/4 pin 
dmf 4.10.15 
Source info: http://www.jst-mfg.com/product/pdf/eng/eXH.pdf 
Note: pin spacing is 2.5 mm 
Note: pins are 0.64 mm square cross section. This means the pin diagonal is 0.905 mm.
Hole diameter spec'd by jst is 0.9 mm; hole diameter used here is 1.0 mm


#### con_Weidmuller_171501000_dmf.lbr
---
Weidmuller 1715010000
LM 3.50/135/2

Screw - Clamping Yoke, Tension Sleeve
14-22 AWG

Weidmuller 1715010000
LM 3.50/135/2

Screw - Clamping Yoke, Tension Sleeve
14-22 AWG
3.5 mm pin spacing. Pins have a rectangular profile, 1.1 x 0.75mm. The drill hole diameter for the original version was too large. Corrected drill size to 1.30mm on 4.22.15.


#### ExtraCore-noProgHeaders_dmf.lbr
---
This version modified to eliminate programming headers that are not directly connected to the underlying PCB. The ExtraCore Package is modified to eliminate programming headers (which are at 90° to PCB outline).


