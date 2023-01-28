# "Writer's Brick" Build Guide

## Parts

1. (1) [Adafruit SHARP Memory Display Breakout](https://www.adafruit.com/product/4694)
2. (1) Raspberry Pi. I'm using a 4 Model B.
3. (1) [Adafruit Universal USB / DC / Solar Lithium Ion/Polymer charger](https://www.adafruit.com/product/4755)
4. (1) 3.7V Lithium Ion Battery Pack. The one I'm using is Adafruit's
   [6600mAh model](https://www.adafruit.com/product/353), but any of their 3.7V
   line would work just as well.
5. (1) enclosure. see the STL files in this repository
6. (1) power switch
7. some jumper wires
8. JST-PH headers

### Optional

- (1) 5mm red LED
- (1) 5mm green LED
- (1) LED resistor
- some protoboard

## Tools

- 2mm hex wrench
- tweezers
- 2 spudgers (or electrically-insulated tweezers)

## Assembly

(TODO)

- place the Brick with the rear face up, the tripod hole pointing toward you
  (and thus the power switch on the left)
- you may want to remove the SD card for slightly easier assembly
- screw lengths
  - battery compartment screws are (2) 25mm M2.5 on the left and (2) 20mm M2.5 on
    the right.
  - PDU compartment uses (2) 16mm M2.5 screws
  - PDU board uses (2-3) 4mm M2.5 screws
  - screen uses (4) 4mm M2.5 screws
  - the screws this uses are M2.5 socket head cap screws, which require a 2mm hex
    driver.
- display jumper cable. from the perspective of the photo. lists are photo-top to photo-bottom.
  - left side. 1x8 header.
    - position 1 (dot): A
    - position 2: B
    - position 3: empty
    - position 4: C
    - position 5: D
    - position 6: E
    - position 7: F
    - position 8 (arrow): G
  - right side. 2x5 header.
    - position 1, front (arrow): C
    - position 1, rear: empty
    - position 2, front: B
    - position 2, rear: G
    - position 3, front: F
    - position 3, rear (dot): D
    - position 4, front: A
    - position 4, rear: empty
    - position 5, front: empty
    - position 5, rear: E
