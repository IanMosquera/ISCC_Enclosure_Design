# Intelligent Solar Charge Controller Enclosure Design Concept



1. With Extruded Aluminum Enclosure (18 x 57 x 96mm)
The design concept uses an extruded aluminum which is made up of two identical extruded aluminum frames with plastic panels at both ends and secured with four screws.
    - The top frame has cutouts for the 
        - screwdriver of the terminal block, 
        - e-ink display, and 
        - navigation button switches.
    - The right side panel (config panel as i call it) has a cutout for usb type c connector. This connector is used to charge, communicate with and configure the ISCC.
    - The left side of panel (IO) has 6 cutouts for both polarities of solar panel (input), battery, and load.
    <center>
        <figure>
            <img src="Initial_Design.png" width="75%">
            <figcaption>Fig. 1. ISCC on Extruded Aluminum</figcaption>
        </figure>
    </center>
2. Tact Switch as Navigation Button
This design uses a custom pcb with five tact swiches as navigation buttons of (UP, DOWN, LEFT, RIGHT and OK). This PCB is connected to the main board through header. The buttons are flushed on the top frame and covered with front panel sticker.

3. Sticker
The sticker is a non-conductive, weather-proof and fade-proof sticker. It has a cutouts for the screwdriver entry and the e-ink display except the navigation buttons. The navigation buttons will be covered but the designated function are indicated via printed graphics on the sticker.

Advantage on this design
- Relatively compact design
- Tact switches provides good tactile feedback to users when pressing the buttons.

Disadvantage on this design
- Components are too cramped inside the enclosure with little to to play for component adjustments.
- Tact switch is prone to wear and tear since it is a mechanical switch. Though wecopuld bypass the navigation button if we encorporate configuration of the ISSC through the USB type C port.