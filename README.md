# [finger_name]

Words about the thing

## Table of Contents

[Manufacture](#manufacture)

[Installation](#installation)

[Usage](#usage)

<!-- [Capabilities and Statistics](#cs) -->

## Manufacture

#### Supplies required
###### Chemicals
* Ease Release 200
* Silicones, Inc. XP-565
* Yellow Print-On Silicone Ink
* Print-On Silicone Ink diluent
* ?mm transparent acrylic
* Gray Print-On Silicone Ink
* Acrylic glue
* Silicone glue
###### Other supplies
* Clear PLA 3D printer filament
* Petri dishes
* Pour boats
* Popsicle mixing sticks
* Pipets
* Needle-tip bottle

#### Equipment required
* Fume hood *(if available)*
* Vacuum chamber
* Toaster oven
* 3D printer
* Laser cutter

A vacuum chamber and toaster oven have been stored in ECE B031 ("silicone lab"), but check with the current project owner for the current location. There are multiple makerspaces on campus which have 3D printers and laser cutters; the two most accessible are the MILL in McCarty Hall and CoMotion Makerspace in Fluke Hall.

### Core procedure
#### 1. Silicone lab
* __Cast transparent gel silicone__: Spray petri dish with Ease Release 200. Mix 15g XP-565, then pour into dish. Vacuum until no bubbles remain, then heat on warm for 10 min.
* __Add yellow layer while XP-565__: Starting with a pinkie-tip quantity of yellow Silicone Ink, mix in a 1:10:60 activator:ink:diluent ratio. The resulting mixture should be approximately the consistency of chocolate milk. Pour in a thin even layer over the XP-565 petri dish. The layer should be as thin as possible, so you will not use all of the yellow silicone. Heat the dish on warm for 15 min.

#### 2. Makerspace
* **Print parts**: Print [core_filename], [corepiece_filename], [shell_filename] open side up in clear PLA with 0.2mm layer height, raft, and no support.
* **Laser cut acrylic**: Laser cut [filename] with vector set to `8s 100p 100f`.
* **Laser cut and engrave gel**: Remove transparent/yellow silicone from petri dish and place yellow-side up in laser cutter. Laser cut [filename] with raster set to `11s 4p 50f` and vector set to `5s 75p 50f`.

#### 3. Silicone lab
* __Cast transparent core silicone__: Mix enough XP-565 to fill the prepared cores, and vacuum in pour boat until most bubbles are gone. 
* __Glue acrylic into core__: Using a needle-tip bottle, apply acrylic glue to the inside of the cores and place acrylic. Make sure the glue gets all the way around the edges, otherwise the silicone will seep past the acrylic and obstruct the camera lens later.
* __Fill core with silicone__: Carefully fill each core with silicone (at or below edge; do not overflow) and vacuum until no bubbles remain, then heat on warm for 5 min. 
* __Add protection layer__: Starting with a half-pinkie-tip quantity *(<1g)* of gray Silicone Ink, mix in a 1:10:40 activator:ink:diluent ratio. The resulting mixture should be somewhat thicker than chocolate milk. Cover the bottom of each cut-out gel with electrical tape and place dot-side up in a petri dish. Using a pipet, cover each gel in gray silicone mix, making sure all untaped sides are covered. 
* __Attach gel to core__: Once cores have cooled, spread a thin layer of mixed XP-565 on each core. Gently place gel on XP-565 layer, being careful to avoid introducing bubbles. Heat on warm for 5 min.

Notes:
* You may find it most efficient to make 4-8 cores at a time with this procedure.
* Mix silicones in a pour boat using a popsicle stick. Use popsicle sticks to portion more viscous materials such as silicone base, and pipets to portion less viscous materials such as activator and diluent. Never use the same pipet or popsicle stick for different materials. 
* PLA parts shrink when exposed to heat. If you plan to modify the core, make your part approximately ?% bigger than actual size in order to account for this.

### Electronics procedure
Wire two Adafruit LED sequins in parallel. Cut and strip a USB cable and solder each LED lead to the appropriate USB cable wire.
[images]

## Assembly and installation
Tap core and shell holes with M2 tap. Attach LEDs to core with transperent double sided tape. Screw core into shell. Attach camera to core with double sided tape, being careful not to force the lens into the hole. Tape wires to shell to provide more stability.

On Kinova hand remove original KG-2 distal phalanxes, being careful not to stretch rubber excessively. Place [finger_name] and screw in shell piece. Continue as if installing original Kinova distal phalanx. Plug both USBs into the wrist controller. The fingers are now ready to use.

## Usage

<!-- ## Capabilities and Statistics <a name="cs"/> -->
