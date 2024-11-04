# Ender-3-Pro-Electronics-Enclosure
Build guide and BOM for converting standard Ender 3 Pro printers to a Voron-inspired electronics enclosure.

This guide is for converting our custom Ender 3 Pro printers (standard bed) to have a Voron-inspired electronics enclosure. The print files are saved on the server, but the original project can be found here for reference:
https://www.printables.com/model/385532-ender-3-pro-voron-themed-electronics-enclosure/comments

The original project doesn’t have very clear instructions, so we’ve written up our own process for utilizing the printed parts. Some of the files have been edited for use with our specific layout, so **download all print files from the server, not the original project.**

See the parts lists below to gather and print everything you'll need for the upgrade before you get started.

# Step by Step Instructions
1. Remove all zipties holding cables to the lower frame and lay the printer on its side
2. Unplug the Y and Z axis cables from the wiring harness. You will need to remove some of the tape and zip ties from the harness to move wires around
3. Add the heat press inserts to the holes indicated below (1a) in the two left and two right grill panels
4. Attach the RPi Mount to the Pi using four M2 screws
5. Use the RPi Shelf to mount the Pi to the SKR board. The shelf screws will also go the whole way through to the SKR mini mount.
6. Run the mini USB cable between the mainboard and the Pi
7. Mount the PSU Hanger to the PSU
8. Follow the mounting layout below to mount all of the electronics
9. Adjust any wire lengths at this point. Update any connectors or plugs that need it as well
10. Flip the printer upright again. Unscrew the Z screw stepper motor and rotate it 90 deg as shown below (2a)
11. Run the cable harness up throguh the slot in the back left deck panel
12. Screw all 4 of the panels down as indicated below (3a)
13. Plug in the Y and Z axis cables from the harness and add zip ties where needed to manage cables

# Mounting Layout
7. Unscrew the PSU from the frame, then remove the mainboard enclosure and screen/Raspberry Pi
8. Remove the plastic base from the PSU. You will have to disconnect the wires from the mainboard to feed them back through the hole.
9. Take the plug adapter off of the plastic base. Break off and sand down the bottom "wing" to make it fit on the grill. Mount the plug adapter to the 'Back Grill Middle' using one M3x16 screww and T nut. The T nut will just span the hexagon space that the screw passes through.
10.

# Build Images
![Alt text](/images/HeatInserts.PNG?raw=true "Heat Press Inserts in Grill Panel")

*1a. Heat press inserts in grill panel*

# Additional Build Notes
- Wire lengths will need to be adjusted once everything is rearranged.
- The screen panel and screen will be completely removed from the printer after this upgrade.

# Printed Parts List
| Part Name | QTY | Material | Color |
| ------------- | ------------- | ------------- | ------------- |
| Deck Left Front | 1 | PETG CF (Push Plastic) | Black |
| Deck Left Back | 1 | PETG CF (Push Plastic) | Black |
| Deck Right Front | 1 | PETG CF (Push Plastic) | Black |
| Deck Left Back | 1 | PETG CF (Push Plastic) | Black |
| Front Grill Left | 1 | PETG (Polymaker) | Yellow |
| Front Grill Right | 1 | PETG (Polymaker) | Yellow |
| Front Grill Middle | 1 | PETG (Polymaker) | Yellow |
| Back Grill Left | 1 | PETG (Polymaker) | Yellow |
| Back Grill Right | 1 | PETG (Polymaker) | Yellow |
| Back Grill Middle | 1 | PETG (Polymaker) | Yellow |
| Foot | 4 | TPU (Polymaker) | Yellow |
| Foot Extension | 4 | PETG (Polymaker) | Yellow |
| PSU Hanger | 1 | PETG CF (Push Plastic) | Black |
| SKR Mini Mount | 1 | PETG CF (Push Plastic) | Black |
| Raspberry Pi Mount | 1 | PETG CF (Push Plastic) | Black |
| Raspberry Pi Shelf | 1 | PETG CF (Push Plastic) | Black |
| Grill Endcap (logo) | 2 | PETG (Polymaker) | Grey |
| Grill Endcap (blank) | 2 | PETG (Polymaker) | Grey |
| 40mm Fan Mount | 1 | PETG CF (Push Plastic) | Black |
| Buck Converter Box | 1 | PETG (Polymaker) | Yellow |

# Hardware BOM
| Part Name | QTY | Use Description |
| ------------- | ------------- | ------------- |
| M2x4 Screws | 4 | To attach RPi to RPi Mount |
| M3 Screws / M3 T Nuts | 2/2 | Mount 4040 fan to printer frame |


