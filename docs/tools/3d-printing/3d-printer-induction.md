# 3D Printing Induction

## The World of 3D Printing

- Types of 3D printing: FDM (fuse deposition modeling), Laser, Resin, Ceramic, Food, Metal printing
- Filament material: PLA, PETG, ABS, ASA, TPU, Nylon and [many others](https://en.wikipedia.org/wiki/3D_printing_filament)
- Printer brands: Prusa, Creality, Ender, LulzBot, Ultimaker, Bambu and many others

The starting point for everyone is **PLA on a FDM 3D Printer**, you can then upskill into more difficult filaments and more advanced 3D printer techniques and printer types once you feel confident in using and FDM printer.

Anyone can easily start by printing models from the internet by searching websites like Printables, Thangs, Thingsverse - [see this wiki page for full list of websites](./links-and-resources.md)

![3D Printing](./images/prusa-manual-img.png)

## Basic steps on how to 3D print

- Find a model online, take note of the specifications of that model, download the files
- Load the files into a slicer software, we use [Prusa Slicer](https://www.prusa3d.com/page/prusaslicer_424/)
- Ensure specifications from your downloaded model are edited into the slicer software
- Slice the model, which will export a .gcode file and load that onto an SD card
- Put the SD card in printer, follow our checklist within the printer area, start the print
- After print ends, clean up printer, pay for filament used (honesty box)
- ... if print the fails, try again printing it again directly from the printer
- ... if after a few attempts it still fails then go back to slicer and make changes to your print settings and export a new .gcode file

## Slicer Software

A Slicer is software that literally 'slices' a 3D models into machine code for the 3D printer to follow (.gcode). This is an essential step in preparing your project for printing on any 3D printer machine. You will import a 3d model into the software and select the correct printer, filament material, print settings (layer height) and infill for your print.

![Slicer](./images/prusa-slicer-img.png)

Here at ReMADE we use [Prusa Slicer](https://www.prusa3d.com/page/prusaslicer_424/) but you are welcome to use [the slicer software of your preference](https://en.wikipedia.org/wiki/Slicer_(3D_printing)), do bare in mind that some 3D printer brands require you to use their official slicer software (i.e. Bambu).

### Basic steps within Slicer settings:
- Import 3D model: right click the file and select 'open with Prusa Slicer'
- Choose **Print Settings**: (0.2 mm is default, our machines are limited to 0.1 mm)
- Select the correct**Filament**: (PLA/PETG/etc and colour)
- Select the correct **Printer**: [see the 3D printers we have at our space](./3d-printers)
- Choose **Supports** : (no/grid/snug/organic)
- Choose **Infill** : (20% is the default, select any range between 10 - 100%)
- Bottom right of slicer software - click on **Slice now**
- The screen will change, in bottom right area you can find the **amount of filament used** and **estimated build time**
- Now the **Slice now** button has become **Export G-code** - click on that and save the .gcode file to you work folder


### Slicer steps & tips
- Ensure the correct printer and filament are selected (follow the specs)
- Select **Draft quality (0.2 mm)** for your first print, as it prints quicker and less waste
- 20% infill is usually OK for most prints, change only if you are looking for something to be extra solid or if your model is very small
- Take note of amount of material (g) and time estimated for print to finish
- Keep a dedicated folder for all your 3D models, gcode exports, slicer sessions and other files on your system for good version control.
- Rename the gcode files to something short with your name and version on it, the printer LCD screen is very small (e.g. Alice-necklace-v1.gcode)
- Move .gcode file to your personal SD card, or bring the file to the makerspace on a USB stick 
- Save your slicer session before closing (this is important for when you will make a v2)


# Risks
- burning of fingers during operation and filament changing - the 3D printer extruder will reach over 200°C so do not touch it.
- crushing hazard during operation - do not place fingers in gears or axis of the printer.
- inhalation of VOCs – do not put your face into the print, selection of filament and using only FDM makes our current setup safe
- fire – the hairspray is flammable and there is slight risk of short circuiting of power-supply of printer (electrical fire) if you spray it whilst the machine is on. Always apply hairspray to the printer sheet when it has been taken off the printer bed.

# Safety

Recommended PPE: light gloves

Emergency stop: the X button below the LCD screen will halt the machine at any time.

In case of fire: unplug the machine first at the wall socket then apply fire-extinguisher to the machine.



# Checklist for 3D Printing - Prusa MK3s

## Prepare to print

- Use two hands and remove the flexible metal print sheet
- De-dust the whole print sheet with soft fabric 
- Use hairspray on the area where your print will be as shown on the slicer software
- Re-align the print sheet by aligning the back of the sheet to the pins first, then setting it down.
![Prusa bed align](./images/prusa-bed-align-img.png)
- The bed is magnetised so the sheet will snap down, do check the alignment on the sides of the bed and adjust if needed.
- Turn on the 3D printer, the switch is located on the back of machine, follow the power cable to find it.
- The LCD screen will flash and the control menu will appear:
![Prusa LCD Screen](./images/prusa-lcd-img.png)
- Press down on the Control Knob like a button, this will open the menu
- Rotate the Control Knob to scroll down and select the **Load filament ** option
- Place your desired filament into the hole located on top of print head, follow the instructions on the LCD screen
- If successful a string of plastic should ooze out of the extruder and the LCD screen will ask if the colour is correct.
- Select 'no' and run the colour check during filament loading process a second time (ensures all extruder is filled and ready)
- Pull away from the extruder nozzle any strings of plastic or any on the build plate using the plastic tool found next to printers
- Select 'yes' in the colour check request, now  the printer is ready.

## Start the print
- Insert SD card on left side of LCD screen (the metal part of SD facing you)
- The LCD screen will update, press down on the Control Knob like a button
- Navigate to ‘Print from SD’, scroll by turning the Control Knob
- Select the correct .gcode file you have prepared (tip: rename your files)
- Select the file by pushing the Control Knob to start the print
- LCD screen will return to the info screen and extruder will start heating up
- The LCD screen shows temperatures of extruder and bed, as well as time remaining for print to finish
- When your target temperatures are attained the printer will start
- Monitor closely the first layers of your print (where most prints fail)
- Plan to be present when print ends (see: bottom right of info screen)
- For long prints, do check on it every hour
- Whilst in print mode the menu changes, if you push the Control Knob then you are able to ‘tune’ the print settings as it print
- Also within the menu you can use the **pause print** and **Change filament** option if you want to change colour
- Most importantly you will also find the **stop print** option - use this option to when your print fails.

**EMERGENCY STOP: the X button below the LCD screen - this will halt the machine in place please only press it once as holding down the X button will reset the machine to default settings**


## End of print

- Wait for the print head to move to 'home' position on the bed
- The print bed will then move forwards towards you
- Using the two points marked with ‘fingerprints’ on the sheet, pull the print sheet off the print bed.
- **CAUTION**: the sheet may still be hot, waiting a minute for it to cool down if advised and improves the print detaching from the sheet
- Once your removed the sheet **GENTLY** flex the print sheet with two hands, this will loosen the print and allows you to push it off without applying much force. The print will not always 'pop' off all times, do not expect this.
![Prusa Flex Bed](./images/prusa-flex-img.png)
- NEVER use metal tools to scrap the print off the print bed sheet, there are plastic tools located near the printers for this purpose.
- If there are traces of the first layer on the print sheet, use the hairspray and the plastic scraper to clean these off.
- Put the print sheet back on the bed and align it as before
- Use the Control Knob, select **Unload filament** and follow instructions on LCD screen and pull the filament out of the print head. 
- If you brought your own SD card, remember to take SD Card with you
- If you brought your own filament take your spool with you - If not please pay for the grams of material you used (there is an honesty box in the printer area)


# Errors & Troubleshooting

### Normal types of 3D printing errors:
- Warping of flat prints on build sheet [link to troubleshoot video](https://www.youtube.com/watch?v=rj0wpGE3uzc&list=PLfzz3f4EgsrRoSc7CIS6mZv88O2H8s44b)
- The print detaches from the build plate - [link to troubleshoot video](https://www.youtube.com/watch?v=bAY6z4IB1U0&list=PLfzz3f4EgsrRoSc7CIS6mZv88O2H8s44b&index=3)
- Blocked nozzle or excess material on nozzle - [link to troubleshoot video](https://www.youtube.com/watch?v=gNXca6k2n1I&list=PLfzz3f4EgsrRoSc7CIS6mZv88O2H8s44b&index=2)
- Birds nest AKA filament non-adhesion
- Layer separation
- Stringing between parts

Report all printer problems or error messages from the printers in the Telegram channel.

**If you don’t report the printer is broken, we won’t know it needs fixing**


# Other wiki links

[list of the 3D printers in our makerspace](./index.md)

[Operating manuals for these 3D printers](./manuals/prusa3d_manual_mk3s_en.pdf)

[Page of links and resources relating to 3D printing](./links-and-resources.md)


**Source of images used:** Prusa - 3D Printing Handbook - [link to full manual](./manuals/prusa3d_manual_mk3s_en.pdf)
