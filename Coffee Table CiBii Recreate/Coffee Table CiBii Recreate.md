The downloaded design of AtFAB CiBii was corrupted, so not usable. Instead we made a new design going from the PDF that was included that was readable. In this sense we are re-creating the table. I do not know if this means that the copyright claim and CC license of the original still holds.

## Lasercutting at RDM Makerspace Rotterdam, The Netherlands (notes)

### Material
- Type: multiplex hardhout (plywood with hardwood)
- Store: Gamma
- Size: 244x122 cm, 18mm
- Price: EUR 53

### Bit
6/8mm negatieve 2 snijder, VHM, Flatnose, Two Flute Centercutting

### Machine
"3D Freesbeest" @RDM Makerspace

### Machine Settings

#### RPM
18,000 RPM (= 300 Hz)

#### Feedrate 
= speed moving through the material 

From table:
- Multiplex 6mm: 5000 mm/s
- Multiplex 8mm: 5500 mm/s

Formulas to calculate:
- Chipload = feedrate / (RPM * amount of flutes)
- Feedrate = RPM * amount of flutes * chipload
- RPM = feedrate / (amount of flutes * RPM)

If:
RPM = 18,000
Flutes = 2
Then:
? (2 variables unknown, feedrate and chipload)

#### Stepdown
= how deep the bit is into the material

- Half the diamter of bit
- 3 or 4 mm

Or use G-wizard to calculate feedrate.

#### Stepover
= distance between the milled paths:

- Bigger = faster, but less accurate
- Smaller = slower and more accurate
- For 2D (from table): 75%

#### Plunge rate
= how fast the bit goes into the material when stepping down

Plunge rate = half feedrate

2500 mm/s

#### Toolpath 
Contour

#### Nulpunten
- Nulpunt Home: is of machine
- Nulpunt Origin: is of material