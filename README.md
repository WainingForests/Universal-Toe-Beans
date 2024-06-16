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

NEW: micro Skree! For the tinest square single key hotswap MX with led possible! Sure it could be alot better, but this was a couple minute project to help a guy out! Should fit Compactyl so no super annoying hand wiring to switch feet!

6/16/2024

Took ages but slowly adding things.
Added MX Choc Royale a SKPCB that has both hotswap sockets on the same pcb! This solution still provides easy soldering points, RGB, and now support for 0806 diodes along with the standard SOD323 diodes all my other designs use.
Added Smallest Single Key PCB for MX! This is just a very simple small SKPCB for tight builds.
Added Roller Encoder SKPCB which has pads for the encoder and a diode for the click. The pcb was designed with specific pads to allow the encoder to 'rotate' onto the pcb preventing the need for pins to be bent while also tightly locking onto the pcb.
Added EC-12 Hollow shaft with LED. This gives you the option to have RGB lit up rotary encoders! Note, this encoder doesn't have a button. 

Roadmap:

Test and revisions
Kailh mouse wheel encoder support (with cutout in center for wheel size support) https://www.kailhswitch.com/mouse-encoder/
maybe swith UG leds to SK6812-EC20 
Hotswap more things?

