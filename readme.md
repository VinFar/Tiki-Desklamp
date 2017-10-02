# An Awesome 3D-Printed Desklamp

<img src=https://github.com/VinFar/Tiki-Desklamp/blob/master/Photos/IMG_20170819_114426.jpg width="600">
<img src=https://github.com/VinFar/Tiki-Desklamp/blob/master/Photos/IMG_20170614_215923.jpg width="600">

This Desklamp is ready-to-print and a remix from the nice looking [Teethy-Tiki-Statue](https://www.thingiverse.com/thing:49334)
from Thingiverse.

The original size of the File is something about 200mm, which is enough to illuminate a big dining table at night,
but not to bright for dazzling people.
#### It is printed with [half transparent red PETG](https://www.dasfilament.de/filament-spulen/petg-1-75-mm/231/petg-filament-1-75-mm-transparent-rot?c=21)
#### other Colors: [blue](https://www.dasfilament.de/filament-spulen/petg-1-75-mm/215/petg-filament-1-75-mm-transparent-blau?c=21) and [green](https://www.dasfilament.de/filament-spulen/petg-1-75-mm/217/petg-filament-1-75-mm-transparent-neongruen?c=21)

#### If you want to scale it you have to watch out that the 18650 Li-ion Battery fits inside the Top!
With the original size there is much space betwenn the Poles of the Battery and the outer shell. It think you can scale to 70% without any problems.
But better double check before printing!

### Printed Lid:

The lid is designed to hold a 18650 Li-ion Battery, [this Li-ion USB-Charger](http://www.ebay.de/itm/5V-MicroUSB-3-7V-Li-ion-18650-Lithium-Battery-Charging-Charger-Module-Protection-/272806392332?hash=item3f8487320c:g:PboAAOSw6btXSwuQ)
, [a simple slide switch](https://www.reichelt.de/Schiebeschalter/T-217/3/index.html?ACTION=3&LA=517&ARTICLE=19976&GROUPID=7595&trstct=lsbght_sldr::19977)
, some cables, a warm-white 3W Power LED and a big heatsink for the LED.
The Lid itself snaps into the bottom part of the Lamp. If everything works fine you can glue it superglue in place.

The Battery snaps easily into the Holder of the Lid. [This little part](https://github.com/VinFar/Tiki-Desklamp/blob/master/Inventor%20Files/steg.stl)
has to be screwed onto the battery. It is a clamp and also the "LED Holder".

On the top of the Lid there are cutouts for the slide switch and the Micro USB Port of the Charger. Everything can be placed using hot glue.
Maybe i will edit this in Version 3.

#### So after printing and assembling the Lid should look like this:
<img src=https://github.com/VinFar/Tiki-Desklamp/blob/master/Photos/IMG_20170819_000211.jpg width="500">

### Power-LED:

The LED can be powered directly from the Battery, but only if you use [this](http://www.ebay.de/itm/4x-Hochleistung-Power-Akku-18650-Lithium-Ionen-mit-je-8800mAh-4-2V-Li-ion-Neu-/282545949755?hash=item41c90d0c3b:g:XWoAAOSw~XpZUq8c)
trashy Li-ion Battery from China. They have a higher internal resistance, so the Voltage automatically drops to a descent Value. 
In addition you can use a 1 - 2 Ohm Resistance or long thin cables in series.
With the shoddy UltraFire Battery the Lamp lasts around 5 hours.

I haven't tried it with high-class Samsung or LG Cells, but if i do so i will post it here. They have about 2200 mAh, so the Light should last much longer.
If you use the better Cells, you definitively should use a Series Resistor! Of course this is not the smartest way to power such a LED,
but there is not much space for a CC Source. Also the voltages are roughly the same, so it is the easiest way!

### [USB-Charger:](http://www.ebay.de/itm/5V-MicroUSB-3-7V-Li-ion-18650-Lithium-Battery-Charging-Charger-Module-Protection-/272806392332?hash=item3f8487320c:g:PboAAOSw6btXSwuQ)

This small Lithium Battery Charger are perfect for this purpose. They are affordable ~1€, small and have many nice protection functions.
Also you can easily charge all types of Lithium Batteries over a Micro USB Port.

#### Features:
- Over-Discharge Protection
- Over-Charge Protection
- Short-Circuit detection
- Overcurrent protection
- Settable Charge Current

These Functions split up into two ICs.
The Charge Current can be set by Resistor R3 in this matter:

| R3 (kOhm) | Charge Current (mA) |
|-----------|----------------|
|10|130|
|5|250|
|4|300|
|3|400|
|2|580|
|1.66|690|
|1.5|780|
|1.33|900|
|1.2|1000|

#### Version 1:
- [This Statue](https://www.thingiverse.com/thing:33746)
- silghtly to small for battery
- no direct place for LED-
- very bad heatsink(aluminium foil)

#### Version 2:
- [This Statue](https://www.thingiverse.com/thing:49334)
- added holder for battery
- added holder for LED
- much bigger and better heatsink
- very shaky, because of the high emphasis

#### Version 3 (ToDo):
- another statue
- put battery and charger into the bottom of the statue, only the LED into the Lid
- better Battery!

### Photos:

<img src=https://github.com/VinFar/Tiki-Desklamp/blob/master/Photos/IMG_20170819_114422.jpg width="500">
<img src=https://github.com/VinFar/Tiki-Desklamp/blob/master/Photos/IMG_20170614_215932.jpg width="500">
<img src=https://github.com/VinFar/Tiki-Desklamp/blob/master/Photos/IMG_20170604_015255.jpg width="500">
<img src=https://github.com/VinFar/Tiki-Desklamp/blob/master/Photos/IMG_20170613_182528.jpg width="500">


