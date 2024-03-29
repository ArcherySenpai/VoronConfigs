

```
I think this will also work...You can use the \n to do a new line so that it is not one long string...
    {action_respond_info("Print_Start Macro Inputs:\n"
                         "BED = %d\n" 
                         "EXTRUDER = %d\n" 
                         "CHAMBER = %d\n"
                         "FL_SIZE == %s\n"
                         "material = %s\n"
                         "Z_Adjust = %.3f\n" 
                         "nozzle = %.2f"\n
                         "filament_name = %s\n" % 
                         (BED, EXTRUDER, CHAMBER, FL_SIZE, material, z_adjust, nozzle, filament_name))}
```


## General

- Bed fans
    - https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Ellis/Bed_Fans
- https://docs.vorondesign.com/community/howto/Takuya/Klicky_Probe_AutoZ_Alternative.html
- ~~mandela plate with magnets~~
    - ~~https://mandalaroseworks.com/products/voron-350-ultraflat-bed~~
    - ~~build plate https://west3d.com/products/double-sided-texture-smooth-flex-plate-with-3m-magnetic-backing-energetic-west3d-collab?variant=41130207445160 (NO MAGNET)~~
    - ~~https://www.fabreeko.com/collections/pei/products/honeybadger-v2-4-single-sided-black-pei-textured?variant=42614568452351~~
    - ~~https://dfh.fm/products/silicone-heating-pad?_pos=10&_sid=da818c221&_ss=r~~

- ~~sensorless end stops for x and y (SEE NOTE AT END)~~
    - ~~https://docs.vorondesign.com/community/howto/clee/sensorless_xy_homing.html~~
- CANBUS WHEN CW2
    - GOOD https://github.com/cruiten/Voron-Related/tree/main/CANbus/Documentation/Umbilical
    - https://github.com/Alexander-T-Moss/Voron-Stuff/tree/main/Mods/%23%20SB2040%20Cooling/STLs
    - https://github.com/allenrowand/voron_mods/tree/main/v2.4
    - https://www.printables.com/model/279739-voron-can-bus-z-chain-move
    - https://github.com/maz0r/klipper_canbus/blob/main/controller/monster8v2.md
    - https://github.com/maz0r/klipper_canbus/blob/main/toolhead/ebb36-42_v1.1.md
    - https://www.teamfdm.com/forums/topic/672-how-to-use-can-toolhead-boards-connected-directly-to-octopus-octopus-pro-on-canboot/
    - https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/LoCoCNC/Strain_Relief_w_Microfit
    - https://github.com/MotorDynamicsLab/LDOVoron2/blob/main/STLs/beefy_raspberry_bracket.stl
    - https://github.com/VoronDesign/Voron-2/blob/Voron2.4/STLs/Electronics_Bay/pcb_din_clip_x3.stl
    - https://github.com/MotorDynamicsLab/LDOVoron2/blob/main/STLs/toolhead_breakout_pcb_bracket.stl
    - https://www.teamfdm.com/files/file/601-bowden-tube-guide/
    - https://github.com/KayosMaker/CANboard_Mounts
    - https://github.com/majarspeed/Misc-Voron/tree/main/StealthBurner%20Umbilical%20cover
    - https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Minsekt/Rear_Umbilical
    - https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/CW2_SB2040_CAN_Umbilical
    - canbus and SB/CWw2 stuff https://github.com/kejar31/VoronMods/tree/main/CB-C2
        - need a fan https://dfh.fm/products/sunon-mf20100v1-1000u-a99-2010-axial-fan?_pos=1&_sid=d08833795&_ss=r
    - Rear cable mount
        - https://github.com/hartk1213/MISC/blob/main/Voron%20Mods/Archived/Voron2.4_umbilical_strain_relief(OLD)/STL/A_Drive/%5Ba%5D_pigtail_cable_cover.stl
        - https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/CW2_SB2040_CAN_Umbilical/STLs
- Macro ideas
    - https://github.com/zellneralex/klipper_config/tree/master
- FINISH ELLIS TUNING
- ~~Mainsail timelapse~~
    - ~~https://www.youtube.com/watch?v=n-BVPidUDLI ~~
    - ~~add to super slicer~~
    - ~~Printer Settings -> Custom G-code -> Before layer change Gcode -> TIMELAPSE_TAKE_FRAME~~
- KlipperScreen?
    - https://klipperscreen.readthedocs.io/en/latest/
- Filament sensor
    - https://www.amazon.com/dp/B07Z97582P/?coliid=I278JGHS5OD8M7&colid=3T6GGJW7T3YSG&psc=1&ref_=lv_ov_lig_dp_it
    - https://www.printables.com/en/model/231626-bigtreetech-smart-filament-sensor-sfs-bracket-for-/files
    - https://www.teamfdm.com/files/file/417-exhaust-cover-sfs/
- Nice screen, what mods to mount it?
    - https://www.amazon.com/BIGTREETECH-Screen-Display-800x480-Raspberry/dp/B08FD2YZ23/ref=sr_1_3?crid=10KRTBYWNXMOD&keywords=tft50&qid=1667860109&sprefix=tft50%2Caps%2C67&sr=8-3&ufe=app_do%3Aamzn1.fos.18ed3cb5-28d5-4975-8bc7-93deae8f9840
    - cheaper still! https://www.aliexpress.us/item/3256801084054417.html
    - Find the case with the cutout on the bottom for brightness
    - https://www.teamfdm.com/files/file/31-btt-pitft50-v2-mount/
- ~~C920 webcam~~
  - ~~https://www.teamfdm.com/files/file/275-c920-mount/~~
  - ~~Mount under z rail https://media.discordapp.net/attachments/710952853514223617/1031599846202822697/20221016_174843.jpg~~



## TO PRINT
- ~~thermistor mount for chamber temp~~
    - ~~https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/jeoje/Z_Chain_Guide_Thermistor_Mount~~
- ~~wago mounts~~
    - ~~https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Boingomw/Wago_mount~~
- ~~270 degree hinges, or other removable ones~~
    - ~~https://github.com/LoganFraser/VoronMods/tree/main/ParametricRemovable270Hinges~~
    - ~~https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/chrisrgonzales/270_degree_hinge~~
    - ~~https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/randell/Door_Hinges~~
- ~~purge bucket/nozzle wipe?~~
   - ~~https://github.com/Ramalama2/Voron-2-Mods/tree/main/Mandalaroseworks/BedPan~~
   - ~~https://www.printables.com/model/201999-nozzle-scrubber-with-a-little-bucket-for-voron-24~~
- ~~Quick release clips~~
  - ~~https://github.com/richardjm/voron-parts/tree/main/voron-2.4/FilamentLatch~~
- ~~nevermore~~
  - ~~https://github.com/nevermore3d/Nevermore_Micro~~
  - ~~https://github.com/MapleLeafMakers/KlipperMacros/blob/main/air_filter_timer.cfg~~
- ~~SB diffuser~~
  - ~~clear filament from LDO kit~~
- ~~z belt cover for led wire~~
  - ~~https://github.com/MotorDynamicsLab/LDOVoron2/blob/main/STLs/z_belt_cover_a_led.stl~~
- ~~exhaust cover~~
  - ~~https://voronregistry.com/mods/fiction-exhaustcoversfs~~
- nozzle holding skirt
  - https://github.com/VoronDesign/VoronUsers/blob/master/printer_mods/README.md
- ~~Top mount spool holder~~
  - ~~https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/elcrni/V2.4-Trident-Spool-Holders~~
- ~~Rock and roll for electronics access~~
  - ~~https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/RockNLol/RockNRoll~~
- ~~Scraper~~
  - ~~https://www.printables.com/model/28337-scraper-for-build-plate-version-2~~
- ~~Updated z joints with bearing~~
  - ~~https://github.com/Annex-Engineering/Other_Printer_Mods/tree/master/VORON_Printers/Reinforced_Gantry_Mounts~~
  - ~~https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_GE5C~~
    - ~~https://kb-3d.com/store/magnets-bearings/323-igus-ge5c-spherical-bearing-eglm-05-igubal-1634423649851.html~~
    - ~~https://kb-3d.com/store/inserts-fasteners-adhesives/288-5x10x1mm-shim-ring-washer-pack-of-50-din988-1634423113147.html~~


## TO BUILD
~~### CW2 VERIFY AGAINST BOM at [https://vorondesign.com/voron_stealthburner](https://vorondesign.com/sourcing_guide?model=VSB)~~
- ~~Delta fan https://west3d.com/products/delta-5015-bfb0524hh-dc24-0-16a-2-pin-cooling-fan~~
- ~~need motor (ordered)~~
- ~~gear kit (ordered)~~
- ~~set ratio to 50:10~~
- ~~reprint face?~~
    - ~~will need fans and leds if so~~
    - ~~https://www.fabreeko.com/products/stealth-burner-pre-soldered-and-crimped-leds?_pos=1&_psq=led&_ss=e&_v=1.0~~
    - ~~https://kb-3d.com/store/fans/501-sunon-5015-blower-fan-24v-maglev-1646515411413.html or https://www.fabreeko.com/products/gdstime-5015-24v-blower-fan?_pos=1&_sid=76b2a2b69&_ss=r~~
    - ~~https://www.fabreeko.com/products/sunon-mag-lev-4010-24v-fan?_pos=1&_psq=4010&_ss=e&_v=1.0~~

# Parts URLs
- Build plates
    - https://www.filamentone.com/products/ultistik-premium-powder-coated-ultem-pei-build-plate-355-x-355-voron-sovol-sv03
- Brushes
    - https://www.aliexpress.us/item/2251832866802617.html?spm=2114.12010615.8148356.2.315e106dfzI86U&gatewayAdapt=glo2usa4itemAdapt&_randl_shipto=US
    - https://www.amazon.com/uxcell%C2%AE-Length-Plastic-Handle-Bristle/dp/B00X9HY5D4
    - https://www.amazon.com/gp/product/B092HWQG69/
- Tubing
    - https://west3d.com/products/capricornus-ptfe-tube-1-9mm-teflonto
    - https://west3d.com/products/bowden-ptfe-tube-4mm-od-2-5mm-id
- Igus cables direct
    - https://www.igus.com/product?artNr=CF10-05-04
- HiWin rails
    - https://magicphoenix.xyz/product/hiwin-mgn12h-rail-z1pm/
    - https://magicphoenix.xyz/product/magicphoenix-mgn9h-rail440c-sus/?cgkit_search_word=mgn9
- Other rails
    - https://west3d.com/products/west3d-printing-mgn12h-1r-300-350-400-linear-rails-with-carriages?variant=42096413376724
    - fabreeko HBs
- Good fans
    - https://www.digikey.ca/en/products/detail/orion-fans/OD4010-24HB01A/2621114
