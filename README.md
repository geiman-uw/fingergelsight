# [finger_name]

Words about the thing

## Table of Contents

* [Manufacture](#manufacture)  
  * [Supplies required](#supplies)  
  * [Core procedure](#coreprocedure)  
  * [Electronics procedure](#electronicsprocedure)  
  * [Assembly and installation](#aandi)  
* [Usage](#usage)
* [Capabilities](#capabilities)

## Manufacture

#### Supplies required<a name="supplies"/>
###### Chemicals
* Ease Release 200
* Silicones, Inc. XP-565
* Yellow Print-On Silicone Ink
* Print-On Silicone Ink diluent
* ?mm transparent acrylic
* Gray Print-On Silicone Ink
* Acrylic glue
<!--* Silicone glue-->
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

A vacuum chamber and toaster oven have been stored in ECE B031 ("silicone lab"), but check with the current project owner for the current location. There are multiple makerspaces at UW which have 3D printers and laser cutters; the two most accessible are the MILL in McCarty Hall and CoMotion Makerspace in Fluke Hall.

### Core procedure<a name="coreprocedure"/>  
Notes:
* You may find it most efficient to make 4-8 cores at a time with this procedure.
* Mix silicones in a pour boat using a popsicle stick. Use popsicle sticks to portion more viscous materials such as silicone base, and pipets to portion less viscous materials such as activator and diluent. Never use the same pipet or popsicle stick for different materials. 
* PLA parts shrink when exposed to heat. If you plan to modify the core, make your part approximately 5% bigger than the intended final size in order to account for this.
#### 1. Silicone lab
* __Cast transparent gel silicone__: After ensuring petri dish is free of dust, spray petri dish with Ease Release 200. Mix 17-18g XP-565, then pour 15g into dish. Vacuum until no bubbles remain, then heat on warm for 10 min.
* __Add yellow layer__: Starting with a 1g of yellow Silicone Ink, mix in a 1:10:60 activator:ink:diluent ratio. The resulting mixture should be approximately the consistency of chocolate milk. Pour in a thin even layer over the XP-565 petri dish. The layer should be as thin as possible, so you will not use all of the yellow silicone. Heat the dish on warm for 15 min.

#### 2. Makerspace
* **Print parts**: Print [core_filename] and [corepiece_filename] in opaque PLA. Print [shell_filename] open side up in clear PLA with 0.2mm layer height, raft, and no support.
* **Laser cut acrylic**: Laser cut [filename] with vector set to `8s 100p 100f`.
* **Laser cut and engrave gel**: Remove transparent/yellow silicone from petri dish and place yellow-side up in laser cutter. Laser cut [gel](fingergelsight/finger_gelsight_production/gelsight_gelpattern_5x14.ai) with raster set to `11s 4p 50f` and vector set to `5s 75p 50f`.

#### 3. Silicone lab
* __Cast transparent core silicone__: Mix enough XP-565 to fill the prepared cores, and vacuum in pour boat until most bubbles are gone. 
* __Glue acrylic into core__: Using a needle-tip bottle, apply acrylic glue to the inside of the cores and place acrylic. Make sure the glue gets all the way around the edges, otherwise the silicone will seep past the acrylic and obstruct the camera lens later.
* __Fill core with silicone__: Carefully fill each core with silicone (at or below edge; do not overflow) and vacuum until no bubbles remain, then heat on warm for 5 min. 
* __Add protection layer__: Starting with 0.5g of gray Silicone Ink, mix in a 1:10:40 activator:ink:diluent ratio. The resulting mixture should be somewhat thicker than chocolate milk. Cover the bottom of each cut-out gel with electrical tape, making sure there are no bubbles where gray silicone could seep under the gel. Place dot-side up in a petri dish. Using a pipet, cover each gel in gray silicone mix, making sure all untaped sides are covered. 
* __Attach gel to core__: Once cores have cooled, spread a thin layer of mixed XP-565 on each core. Gently place gel on XP-565 layer, being careful to avoid introducing bubbles. Heat on warm for 5 min.

### Electronics procedure<a name="electronicsprocedure"/>
Wire two Adafruit LED sequins in parallel. Cut and strip a USB cable and solder each LED lead to the appropriate USB cable wire.
[images]

### Assembly and installation<a name="aandi"/>
Tap core and shell holes with M2 tap. Attach LEDs to core with transperent double sided tape. Screw core into shell. Attach camera to core with double sided tape, being careful not to force the lens into the hole. Tape wires to shell to provide more stability.

On Kinova hand remove original KG-2 distal phalanxes, being careful not to stretch rubber excessively. Place [finger_name] and screw in shell piece. Continue as if installing original Kinova distal phalanx. Plug both USBs into the wrist controller. The fingers are now ready to use.

## Usage

## Capabilities
