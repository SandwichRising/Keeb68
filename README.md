# Keeb68
Custom designed tool-free hotswap PCB and Case to make a 68 key keyboard.

<br>

<img src="./media/keeb68.jpg" width="1000">

<br>

This custom keyboard PCB was originally made as a surprise for a friend who enjoys keyboards, and turned out well enough that I thought I'd post it back open-source to the community, which is where I also learned from. Specifically, Masterzen and his [keyboard design tutorial](https://www.masterzen.fr/2020/05/03/designing-a-keyboard-part-1/) went a long way in bridging my knowledge gaps and bringing this project to life.

<br>

Currently this repo is a buildlog and is being actively updated. It will also include the full keyboard design files once I create new artwork for the open-source release. 

<br>

## Buildlog:

### KiCad Design

<br>

I was already familiar in designing with and programming the ATmega32U4 used as the keyboard's brain, and after learning about how to make keyboards using online resources I designed the PCB in KiCad to be compatible with existing QMK firmware using a 68-key layout. 

<img src="./media/kicad_render_1.jpg" width="500">
<img src="./media/kicad_render_2.jpg" width="500">
<img src="./media/layout.png" width="500">

<br>

<br>

### Physical Assembly of PCBs

Once the PCBs and components arrived, a hot air gun and soldering iron were used to assemble and solder the PCBs by hand. A syringe of soldering paste was used along with tweezers to place SMD components that were then heated into place by the hot air gun. 

<br>

Most of the tools used in assembly can be seen in this picture, except the hot air gun:

<img src="./media/tools.jpg" width="500">

<br>

The is a view of the hot air nozzle heating a processor into place:

<img src="./media/hotair.jpg" width="500">

<br>

This is a view of two completed keyboard processors soldered into place:

<img src="./media/soldered_computers.jpg" width="500">

<br>

<br>

### 3D Printed Case

While I soldered the PCBs and worked on the CNC process for the wooden case, my friend quickly designed a 3d printable case to allow us to use the keyboards immediately. The case could be printed in multiple pieces on an ender3 printer, and then metal supports, glue, and heat were used to combine the parts into larger pieces.

<img src="./media/prototype_pla_2.jpg" width="500">
<img src="./media/prototype_pla_1.jpg" width="500">
<img src="./media/3dcase.jpg" width="500">

<br>

<br>

### Wooden CNC Case

The cases were designed to be cut from two separate pieces of wood stock to make two main parts: a plate and a base. The PCB was designed before the case, leaving the corners cut out in a round shape to aid in future design. This cornerspace could be used for screwholes, or as in the actual case, alignment posts connected to the plate. The final case design uses these alignment posts on the backside of the plate to hold the PCB in place laterally as well as holding the plate aligned into the base of the case. Between the alignment posts and the tension of the connection to the switches through the hot-swap connectors, the PCB is held firmly in place without screws, appearing to float on the back of the plate. The plate also rests into slots cut into the base to marry the plate, base, and PCB together without screws. This allows the keyboard to be used normally without anything shifting around due to typing, and also allows easy removal of the plate by lifting upward, exposing the inside of the case. Since the PCB is hot-swap designed, and all pieces friction fit together, this allows full assembly and dissably without any screws (besides the key stabilizers). However, to add LEDs, they must be soldered in as the backlight design was experimental in nature. 

<br>

The design of the case required machining both the top and bottom of a blank into a plate or base. A custom technique was developed using alignment pegs at known locations inserted through the piece of stock and into the bed of the CNC machine, allowing dual-side cutting to sub-mm alignment tolerances. This allowed cutting and then flipping a workpiece to machine both sides of each part accurately. 

<br>

Stock material (sapele wood) used to make a case or plate:

<img src="./media/stock.jpg" width="500">

<br>

A view of the top cut finished for a new plate:

<img src="./media/plate_cut_top.jpg" width="500">

<br>

Views of the bottom cut for a new plate, early on and then almost finished:

<img src="./media/plate_cut_bottom1.jpg" width="500">
<img src="./media/plate_cut_bottom_2.jpg" width="500">

<br>

A lightweight prototype pine case and detachable foot in a machined frame, used to test the cuts for fitment and accuracy:
<img src="./media/prototype_base.jpg" width="500">
<img src="./media/prototype_base_back.jpg" width="500">

<br>

After carving out the inside of the case, it's flat surface was layered in painter's tape. The artwork was then CNC engraved through the tape and into the case, leaving a tape mask to paint over. Depending on the specifics of the tape and CNC programming used, there was a varying amount of cleanup work that needed done to the mask by hand after finishing the CNC carve. The mask was then sprayed with paint and removed, leaving only the engravings painted. A protective polyurethane coating was then applied. The lettering on the backside of the plates was done with the same technique.

<img src="./media/prototype_mask.jpg" width="500">
<img src="./media/engraved_gaben.jpg" width="500">
<img src="./media/engraved_lettering.jpg" width="500">
<img src="./media/engraved_cleanup.jpg" width="500">
<img src="./media/drying_case.jpg" width="500">
<img src="./media/plate_2.jpg" width="500">

<br>

Some additional pictures of the finished keyboards:

<img src="./media/base_bottom.jpg" width="500">
<img src="./media/3parts_display.jpg" width="500">
<img src="./media/usb_port.JPG" width="500">
<img src="./media/case_and_cat.JPG" width="500">
<img src="./media/parts_display.jpg" width="500">
<img src="./media/plate.JPG" width="500">
<img src="./media/pcb.jpg" width="500">

<br>

<br>

<br>

There will be more here in the future, including design files for both the case and PCB.

Thanks for taking a look!

