Changelog:
2024-05-22 
SHCS for the rail mounting didn't fit; I hadn't realized this earlier because it's a factor that changed from when I was using tiger3dprintings cad as a base for my changes.
Belt clips need an increase in tolerance for the excess belt section.
Change the back screws to all be bottom mounted, So the duct can be installed after going onto the linear rail. As a result, Aluminum foil tape has been added to the BOM + will be used to cover the screw holes.
Beacon Sherlock gave more clearance + better strain relief (SLM Duct Changes)
Rail mounting screws were changed to M3x8mm SHCS

BOM Changes
4x M3x8mm SHCS (added)
4x M3X10mm SHCS (removed)
Aluminum Foil for ducts (added)

Have an older version of takeoff. What parts are reusable?
The Mainbody + Duct are the only parts that are not reusable with the current changes. I initially decided that for better airflow characteristics, the maintenance far outweighs the cons when you use aluminum foil to cover those sections.

2024-06-01
Add support for orbiter v2

2024-08-15
# Takeoff V2!
So much has changed now, I don't quite know where to start. Belt Clips have been ditched, instead I designed a monolith and voron belt path! The idea being that you feed the belt thru the belt path twice so that it exits beside itself. It's feed beside a circular SLM feature so that the belts are parrallel and able to clamp without a custom option for monolith!

I added support for MGN9H with a spacer, I'll still live by mgn12h since the toolhead is heavy, extra support is always recommended with extra heft!

Reduced the thickness of the chube mounting surface from 6mm ish to 3.4mm

Added way more ziptie slots

Made the top plate two main options, A or B

Added the stylish Purrfectttt Options for A or B

Added a laser cut top plate for those who don't use a sherpa K face

Added holes for dragon pattern hotends

Many of the geometry has changed so I won't be noting it all down. Most of the changes occured in my discord

BOM Changes

Bye bye clip specific hardware!

x2 4mm OD x 3mm ID x 22.5mm L Steel tubes (removed)

x2 SLM Printed Belt Clips (removed)


1 less M3x35mm (removed)
M3x35mm Switched to BHCS focused due to the duct


x2 Laser Cut Belt Clamps  (added)


x4 M3x8mm SHCS/BHCS (removed)


x2 M3x10mm FHCS (removed)
x2 M3x8mm FHCS (added)


MGN9H Specific:

1x MGN9H 3mm Spacer (Accept unparrallel belts with a 1/8" spacer as an american or sand it down!) (added)

x4 M3x8 SHCS/BHCS (added)


MGN12H Specific:

x4 M3x6mm SHCS/BHCS (SHCS is just better don't @ me.) (added)


Chube: x6 M3x16mm SHCS/BHCS (removed)
x6 M3x12mm SHCS/BHCS (added)


2024-09-03
V2.1 

This update was alot smaller, I had parts come in from in3dtec that had worked but could use a bit more tolerancing. 

Ziptie slots had width tolerances changed from 2.8mm to 3.3mm (chube wire holes)/ 3.1mm (in whiskers) ![alt text](https://i.gyazo.com/6e2ee35f38c17a7003ab9c5c4a4f7c74.png)

The bowden tube hole was changed from 4.3mm to 4.4mm as it was a bit too snug ![alt text](https://i.gyazo.com/e04a09f296d95e4ea08a01b6428f8323.png)

The radius before belts exit was changed from .5mm - 1mm ![alt text](https://i.gyazo.com/8f10509e1e3be621eca2221497f8200f.png)

2024-10-21

This update adds cad for goliath air fdm ducts, chube fdm ducts, a watercooled mainbody and updates the top plate A for 1 which doesn't have extra holes mean't for a change that I reversed. (Was going to have the top plate mountable from top or bottom but didn't fit well)