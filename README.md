# Motorized-kinetic-Steam-logo-3D-printed

This is a large-scale motorized kinetic Steam logo that moves just like a real piston with adjustable speed.

## About

The whole thing is printed from normal PLA and is about 50cm long. I recommend a white color for most authentic results. It is mounted to a stand made from 3030 T-slot aluminum profiles.

A 12V DC motor is mounted to the right rotary side of the logo. When it spins, it moves just like a real Steam piston. It uses a similar system like a 3D printer - the carriage is mounted on three LM8UU linear bearings sliding on two rods. You can control the speed with a PWM controller (enclosure for module coming soon).

The whole idea actually came from a random meme gif - the Gaben Steam Sale meme. When I saw it somewhere in Instagram comments, the idea of making this real started forming in my head. So I downloaded the old Steam logo and started modeling in Fusion 360, and a few days of modeling later... there it was!

I haven't printed and built it yet because I am missing a lot of hardware and currently waiting for Hack Club Blueprint grant program to approve.

![steam](https://github.com/user-attachments/assets/a2f2ea41-38a0-44be-b055-1ff2684c1461)


## Visuals

### Front view

<img width="1176" height="854" alt="image" src="https://github.com/user-attachments/assets/411d2289-52ea-402b-88b7-87db5c2acfde" />

<img width="1568" height="675" alt="image" src="https://github.com/user-attachments/assets/25657d78-8da5-47c9-b521-2c7a9e45c19b" />

### Back view

<img width="1172" height="685" alt="image" src="https://github.com/user-attachments/assets/92a08b42-bc6f-41a2-ad73-38d62166b6cf" />

<img width="825" height="791" alt="image" src="https://github.com/user-attachments/assets/274ae48d-0323-4620-8c5f-747b3577b3aa" />

### Detail of the piston carriage

<img width="831" height="906" alt="image" src="https://github.com/user-attachments/assets/9c16e355-6348-4953-af8a-604c89182fba" />

### Wiring diagram

Wiring: 12V PSU → PWM controller → motor

## Getting Started

### Parts Required

See **BOM.csv** for complete list with links, or at the bottom of this file.

### Tools Needed

- Good calibrated 3D printer (PLA recommended)
- Soldering iron (for heat-set inserts)
- Basic hand tools (screwdrivers, allen keys)
- Superglue

### Assembly

1. **Print all parts** - Print the carriage, covers, motor mount, arm, and profile mount in PLA

2. **Install heat-set inserts** - Use soldering iron to insert M3 threaded inserts into the carriage and shaft mount

3. **Assemble the carriage** - Insert LM8UU bearings into the carriage, attach covers with M3 screws

4. **Attach rods end brackets** - Both rods slide into bracket with motor holder, slide carriage on to the rods and secure with second bracket on other end

5. **Mount the motor** - Place motor into motor mount, secure with grubscrew on shaft and two M3x6 screws

6. **Connect arm mechanism** - Use 608ZZ bearings, M8 screws and nuts to connect both arms to carriage and slide the end of shaft into rotary arm and secure with a little of superglue

7. **Build the frame** - Connect 3030 profiles using corner brackets and M4 T-nuts, it should look like two upside down T's connected at ground with longer one profile in middle

8. **Attach the whole mechanism** - Secure printed brackets to frame with M4 screws and T-nuts

9. **Wire electronics** - Connect motor to PWM controller, connect power adapter

## Usage

1. Connect 12V power adapter
2. Turn the PWM potentiometer to adjust speed
3. Watch the Steam logo piston move!

## Files

| File | Description |
|------|-------------|
| `steam logo.step` | STEP file of complete 3D model |
| `steam logo.f3d` | Fusion 360 source file |
| `BOM.csv` | Bill of Materials with links |
| `wiring_diagram.svg` | Wiring schematic |

## Author

Julian Blahák

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Design Phase - CAD Model and Documentation

- Designed 3D model in Fusion 360 (~15h)
- Researched and selected components (~2h)
- Created BOM with links (~3h)
- Wrote documentation and README (~4h)
- Total time: approximately 24 hours

## BOM

Category,Item,Need (pcs),Pack Size,Status,Link

Electronics,DC Motor JGA25-370 12V 60RPM,1,1,Buy,https://www.laskakit.cz/motor-jga25-370-12v-s-prevodovkou-/

Electronics,PWM Potentiometer Controller,1,1,Buy,https://www.laskakit.cz/pwm-regulator-otacek-motoru-3a/

Electronics,12V Power Adapter,1,1,Buy,https://www.laskakit.cz/napajeci-adapter-sitovy-1000ma-5-5-2-1-mm-12v/

Electronics,DC 5.5/2.1mm Female Connector,1,1,Buy,https://www.laskakit.cz/konektor-dc-5-5-2-1mm-samice-25cm-kabel/

Linear Motion,8mm Smooth Linear Rod 500mm,2,2,Buy,https://www.amazon.de/-/en/Straight-Diameter-Horizontal-Precision-Bearing/dp/B08XYNLPGP

Linear Motion,LM8UU Linear Bearing,3,8,Buy,https://www.amazon.de/-/en/QUARKZMAN-Bearings-Diameter-Bearing-Printer/dp/B0CNXJZ62C

Linear Motion,608ZZ Bearing,2,10,Already own,https://www.amazon.de/-/en/Bearings-Miniature-Precision-Skateboards-Rollerblades/dp/B0F9TCDTSJ

Screws M4,M4x18 Screw,8,848,Already own,https://www.amazon.de/-/en/RunXinDa-Piece-Screws-Nuts-Assortment/dp/B0FXQF4FH9

Screws M4,M4x14 Screw,4,848,Already own,https://www.amazon.de/-/en/RunXinDa-Piece-Screws-Nuts-Assortment/dp/B0FXQF4FH9

Screws M4,M4 T-Nut for 3030 Extrusion,12,10,Buy (2 packs),https://www.amazon.de/-/en/METALLIXITY-Sliding-attachment-aluminium-extrusion/dp/B0D89NW4F7

Screws M3,M3x16 Screw,10,520,Already own,https://www.amazon.de/-/en/Hexagonal-Cylinder-Stainless-Threaded-Assortment/dp/B0FVXX812W

Screws M3,M3x6 Screw (for motor),2,520,Already own,https://www.amazon.de/-/en/Hexagonal-Cylinder-Stainless-Threaded-Assortment/dp/B0FVXX812W

Screws M3,M3x6 Grub Screw,1,676,Already own,https://www.amazon.de/-/en/Foliv-Screws-Assortment-Hexagon-Hexagonal/dp/B0BX34P7NZ

Inserts,M3x3 CNC Kitchen Threaded Insert,11,50,Buy,https://www.amazon.de/-/en/CNC-KITCHEN-Original-Threaded-Version/dp/B09FXNX6WF

Screws M8,M8x25 Phillips Pan Head Screw,2,30,Buy,https://www.amazon.de/-/en/Zuyya-Screws-Socket-Stainless-Thread/dp/B0FKSQWG9D

Screws M8,M8 Nut,2,50,Buy,https://www.amazon.de/-/en/Topnorm24-Hexagonal-Stainless-High-Quality-Rustproof/dp/B0C3YCF3BM

Tools,Soldering Iron Tips Adapter ERSA,1,1,Buy,https://www.amazon.de/-/en/gp/product/B0D9YFZN91

Tools,Melting Aid Set for Inserts,1,1,Buy,https://www.amazon.de/-/en/gp/product/B0DP51DDF7

3030 Profiles,3030 Aluminum Profile 340mm,4,-,Already own,https://vslot-czech.cz/cs_CZ/p/Hlinikovy-profil-cerny-30x30-8-K-ROZMERU/3744

3030 Profiles,3030 Aluminum Profile 465mm,1,-,Already own,https://vslot-czech.cz/cs_CZ/p/Hlinikovy-profil-cerny-30x30-8-K-ROZMERU/3744

3030 Profiles,3030 Corner Bracket,10,10,Buy,https://www.amazon.de/-/en/Befenybay-Extruded-Aluminium-Extrusion-3030-Black-10/dp/B0BJQ93GLV
