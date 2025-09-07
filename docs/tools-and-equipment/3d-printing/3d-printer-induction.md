# 3D Printing Induction

## The World of 3D Printing
Types of 3D printing: FDM (fuse deposition modeling), Laser (SLS, DMLS, EBM), Resin, Ceramic, Food, Metal printing
Filament material: PLA, PETG, ABS, TPU, Nylon and many others
Printer brands: Prusa, Creality, Ender, LulzBot, Ultimaker, Bambu
Ideas of what to print: repair broken plastic parts, custom spacers, prototypes, figurines, functional prints, organisers, print-in-place
Future of 3D printing: medical devices, bone implants, prosthesics, whole buildings, custom metal manufacturing

The starting point for everyone is PLA on a FDM 3D Printer, you can then upskill into more difficult filaments and more advanced 3D printer types.

You can easily start by printing models from the internet:
Printables, Thangs, Thingsverse: See this wiki page (CREATE: 3D printing resources page)>

… or you can design your own 3D models to manufacture your unique design, but this requires learning 3D modeling software

![3D Printing](./images/prusa-manual-img.png)

## How to 3D print (easy mode)

- Find a model online, take note of specifications, download file(s)
- Load the files into a slicer software (we use Prusa Slicer)
![Slicer](./images/prusa-slicer-img.png)
- Ensure specifications are edited in your slicer software
- Slice the model into a .gcode file and load that onto an SD card
- Put the SD card in printer, follow our checklist, start the print
- Print ends, clean up printer, pay for filament used (honesty box)
- ... if print fails, go back to slicer and make a v2 of project

## Slicer Software

A Slicer is a program or piece of software that helps you 'slice' a 3D models in .stl file format into machine code for the 3D printer to follow. This is an essential step in preparing your project for printing on any machine. Here at ReMADE we use Prusa Slicer but you are welcome to use the slicer software of your preference, do bare in mind that some brands require you to use their slicer software (i.e. Bambu).

### Important Slicer settings:
- Supports : (yes/no)
- Build plate adhesion : (yes/no)
- Print settings / Layer height	: (0.2 mm default, limit 0.1 mm)
- Infill : (20% default, select a range between 10 - 85%)

### Slicer steps & tips
- Ensure the correct printer and filament are selected (follow the specs)
- Draft quality (0.2 mm) for your first print, as it prints quicker / less waste
- Take note of amount of material (g) and time estimate for print to finish
- Press the Slice button (bottom right of screen) and save the .gcode file
- Rename the .gcode file, make a copy for your personal project folder
- Move .gcode file to the SD card or bring it makerspace on a USB stick 
- Save your slicer session before closing (important if you want a v2)


# Risks & Safety
- Risk: burning and crushing hazard during operation
- Risk: inhalation of VOCs whilst plastic is melted at 200+ degrees – do not put your face into the print, selection of filament and only FDM makes our current setup safe
- Risk: fire – the hairspray is flammable and slight risk of short circuiting of power-supply of printer (electrical fire)

Recommended PPE: Gloves

Emergency stop: the X button below the LCD screen

In case of fire: unplug the machine first, then apply fire-extinguisher


# Errors & Troubleshooting

## Normal types of 3D printing errors:
- Birds nest (filament non-adhesion)​: (add link to some video / guide)
- The print detaches from the build plate (add link to some video / guide)​ 
- Blocked nozzle or excess material on nozzle (add link to some video / guide)

Report all other printer problems or error messages from the printers in the Telegram channel.

If you don’t report the printer is broken, we won’t know it needs fixing


# 3D Printing - Prusa MK3s

## Prepare to print

- Use two hands and remove the flexible metal print sheet
- De-dust the whole print sheet with soft fabric 
- Use hairspray on the area where your print will be (see: slicer software)
- Re-align the print sheet as shown
![Prusa bed align](./images/prusa-bed-align-img.png)
- Turn on the 3D printer (switch is located on the back of machine)
- Use the LCD control menu:
![Prusa LCD Screen](./images/prusa-lcd-img.png)
-- Press the Control Knob like a button
-- Rotate the knob and select ‘Load filament’ 
-- Place filament into the hole on top of print head
-- Run the colour check during filament loading process TWICE
- Clean nozzle with plastic tool found next to printers


## Start the print
- Insert SD card on left side of LCD screen (metal part facing you)
- The LCD screen will update, press the Control Knob like a button
- Navigate to ‘Print from SD’, scroll by turning the Control Knob
- Select the correct .gcode file you have prepared (tip: rename your files)
- Select the file by pushing the button to start the print
- LCD screen will return to info screen and extruder will start heating up
- When your target temperatures are attained the printer will start
- Monitor closely the first layers of your print (where most prints fail)
- Plan to be present when print ends (see: bottom right of info screen)
- For long prints, do check on it every hour
- Whilst in print mode the menu on the LCD screen changes, if you push the Control Knob then you are able to ‘tune’ the print settings ‘on-the-fly’ 
- Within the menu you can use the ‘pause print’ and ‘stop print’ options

**EMERGENCY STOP: the X button below the LCD screen - Just press once, holding down the X button resets the printer settings**


## End of print

- Wait for the print head to move to 'home' position on the bed
- The print bed will then move forwards towards you
- Pull the print bed sheet off the printer, there are two points marked with ‘fingerprints’ on the sheet for this purpose. (CAUTION: HOT)
- GENTLY flex the print sheet with two hands, this will loosen the print and allows you to push it off without applying much force. The print will not always 'pop' off all times, do not expect this.
![Prusa Flex Bed](./images/prusa-flex-img.png)
- NEVER use metal tools to scrap the print off the print bed sheet, there are plastic tools located near the printers for this purpose.
- If there are traces of the first layer on the print sheet, use the hairspray and the plastic scraper to clean these off.
- Use the Control Knob, select ‘unload filament’, follow instructions on LCD screen and pull the filament out of the print head. 
- If you brought your own: Take SD Card and filament spool
- If not, pay for the grams of material you used with honesty box


