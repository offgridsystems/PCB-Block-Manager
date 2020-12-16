I'm going to do the V2 changes in the typical engineering WAS/IS format, as I think that is the clearest way to proceed.
So....
WAS:                                                                    
1. Teensy LC (for Block Manager - Teensy 3.1 for Pack Sup)                
2. Used fan for cooling                                                    
3. POT used for manually adjusting BMS voltage                             
4. Tact switch used for user control and learn blocks mode                 
5. Connector footprints were not perfect                                   
6. A little expensive  
7. 2.4Mhz comms, non-secure comms

==================================================================
IS:
 1. TI CC1310 ARM chip with sub-Ghz radio on board
 2. Distributed BMS shunt resistors with smaller parts so fan is not needed but fan footprint retained 
 3. POT still on board but not stuffed (DNS) for this version
 4. Tact switch AND capacitive switch added for same
 5. Adjust footprints slightly to fit clamp boards for better plug and play
 6. Lower cost to build, especially through JLC-PCB using their auto loaded parts. 
 7. 900Mhz comms, security enabled, more robust comms, longer range
