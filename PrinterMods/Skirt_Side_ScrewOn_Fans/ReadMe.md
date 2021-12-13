# Screw On Side Fan Support
I wanted a way to mount the 6020 fans with screws and add covers with grills to prevent little fingers from getting in. This is what I came up with to allow me to easily mount different possible fan covers with a new fan support skirt piece. I will also be able to re-use the fan cover for the exhaust fan on the back if I choose.

My first cover design
![Square Fan Covers](https://github.com/AsterDW/Voron/blob/master/PrinterMods/Skirt_Side_ScrewOn_Fans/Images/Fan%20Support%20Render.png)

Inspired by the Stealthburner I wanted to try integrating the hexagon shape into the front of the covers.
![Hex Fan Cover](https://github.com/AsterDW/Voron/blob/master/PrinterMods/Skirt_Side_ScrewOn_Fans/Images/HexCoverRender.png)

## Layout
- Step files are located in the CAD folder
- 3mf exports of all the components are in the Models folder tree
  - Each fan cover has its own sub folder with the cover and the grill.

## Printing
- All parts were printed with the standard Voron printing guidelines.
  - 4 shells
  - 40% infill
  - .4 mm line width
  - .2 mm layer height (except where noted otherwise)
- This uses a custom version of the side fan support. **side_screw_on_fan_support_x2.3mf** replaces the original side_fan_support_x2.stl model. This provides a fan tray and holes for the screws.
- Each Fan Cover style is a two piece design. A model for the cover and a model for the grill.
  - Print each piece seperately for accent color and then assemble them. These are intended to be a press fit and you may need to use a wide flat head screw driver around the edges of the logo to finish the press fit. These are designed with a .2mm offset between the mating faces, but there are enough to make it a tight fit.
  - **Hex Cover** One deviation from the standard print settings. The Hex cover with the slope transitioning from the square shape to the hexagon is steep. I printed this part using adaptive layer height from 30% minimum and 50% maximum (.12mm - .2mm). For a smooth look I would suggest reducing the layer height for printing either using a smaller layer height in general. The piece will print fine at normal .2mm but it will show the steps more clearly.

## Assembly Layout - Standard
![Exploded View](https://github.com/AsterDW/Voron/blob/master/PrinterMods/Skirt_Side_ScrewOn_Fans/Images/ExplodedView.png)

## BOM
I have broken out the custom bits based on the mounting being used below. Note you will still need the standard heat set inserts and screws used to mount the original Voron side_fan_support part to the printer.
**With Fans**
- M3 x 25mm Button Head Cap Screws
- M3 Nuts

**Without fan, Covers Only**
- M3 x 8mm Button Head Cap Screws
- M3 Nuts

**Optional - Use Threaded Inserts**
![Threaded inserts](https://github.com/AsterDW/Voron/blob/master/PrinterMods/Skirt_Side_ScrewOn_Fans/Images/Optional_Threaded_Insert.jpg)
I found the mounting holes in the fans were perfect size to insert heat set threaded inserts into the back side of the holes and then screw in from the back.
In hindsight it probably would have been easier to set the threaded inserts into the front side of the fan and then I could have used either M3 x 8 or M3 x 10mm screws.
- M3 x 5mm OD heat set inserts
- M3 x 22mm Button Head Cap Screws
