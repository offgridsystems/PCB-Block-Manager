I'm going to do the V2 changes in the typical engineering WAS/IS format, as I think that is the clearest way to proceed.
So....
WAS:                                                                    IS:
Teensy LC (for Block Manager - Teensy 3.1 for Pack Sup)                 TI CC1310 ARM chip with sub-Ghz radio on board
Used fan for cooling                                                    Distributed BMS shunt resistors with smaller parts so fan is not needed but fan footprint retained 
POT used for manually adjusting BMS voltage                             POT still on board but not stuffed (DNS) for this version
Tact switch used for user control and learn blocks mode                 Tact switch AND capacitive switch added for same
Connector footprints were not perfect                                   Adjust footprints slightly to fit clamp boards for better plug and play
A little expensive                                                      Lower cost to build, especially through JLC-PCB using their auto loaded parts. 
