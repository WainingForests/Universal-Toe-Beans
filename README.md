# Universal-Toe-Beans
Single key pcb design with back lighting for MX, Choc v1, and EC11 (with hotswap)


Currently in a non-tested version. These will allow for easy ribbon soldering across with 30-28awg silicone parallel wire. 
LIGHTING comes in two different sets!
Firstly, MX and CHOC versions have per key RGB that is upward facing. This is supplied by SK6812MINI-E SMD components. When purchasing these MAKE SURE the pad layout matches. I've heard of some chinese versions being different. THEY MUST have the extended legs otherwise it is like that the pad layout isn't compatible.

UG pads (VCCUG and DI DO UG) are for Underglow lighting. This is also PER KEY RGB but instead supplied by WS2812B. These are super small at a 1010 package. (1mmx1mmx.8mm). They're rated for the same voltage as the up facing, but I supplied a separate power line to make sure there isn't weird supply issues. 

IF testing proves I need decoupling capacitors I'll try and fit them, but it'll be likely that the underglow rgbs will have to be removed for tracing fitment.

Diodes are 1N4007WS (sod-323 package size), in a Col2Row arrangement. (negative to R pad, positive to switch pad). 

EC-11 pcbs; 
These will be updated but should work currently. 

I'll have all of these on order in small quantities to text and make revisions. USE AT YOUR OWN RISK!


Roadmap:

Test and revisions
Kailh mouse wheel encoder support (with cutout in center for wheel size support) https://www.kailhswitch.com/mouse-encoder/
maybe swith UG leds to SK6812-EC20 
Hotswap more things?
