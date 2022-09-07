# Mantis Xol
![image](https://user-images.githubusercontent.com/86749712/170899561-c6480bd5-9b96-462e-881a-725765ba0ca0.png)

## Description
Originally a project to slap 5020 blower fans onto Mantis, this toolhead variant started as an attempt to improve parts cooling, spurred on by Derpimus' noted cooling woes on his DOOMCube. After finding that the 5020s were just plain too fat to fit without looking like a standard Ender 3 Thingiverse special, I abandoned the large fan dream in favor of better cooling efficiency and lighter weight. This new and improved dream was also corrupted by my then budding and now all-consuming love for worm gears.

## Coming Soon: Xol 2
![image](Images/Xol2Preview.png)
 - Cooler: Still a little ugly but better
 - Lighter: 260g-ish for Sherpa Mini
 - Rigid-er: I want to throw this thing across the room
 - *a second supported hotend*
 - also every feature below
 
#### Features:
 - Lighter weight (285g Sherpa Mini/300g DFA vs Stealthburner's 430g)
 - Better airflow than Stealthburner (6-7 CFM through short ducts vs 4.6-5.2 CFM through long ducts)
 - Improved resonance management compared to Mantis 5015
 - Support for Sherpa Mini-pattern extruder mounting as well as Annex Engineering's **Double Folded Ascender** worm gear extruder
 - Support for JosAr's Klicky, VinnyCordeiro and WhoppingPochard's PCB Klicky, and Nionio6915's Euclid
 - Nozzle LEDs. They're not the best but they're there.
 
#### Future Development (No ETA):
 - Bracing for PCB mounts
 - Rev 2 for ducts since the current version punishes curling too harshly and might be too low for some nozzles
 - Quickdraw 2 support
 - Update DFA Bottom to latest version for slightly better heatset quality of life
 - Revo support

![image](https://cdn.discordapp.com/attachments/895643441193697300/992596124760277013/SPOILER_20220608_165455.jpg)
## Note:
I'm not the owner of some of the STLs in this repo. The rightful owners are included in the filenames and these files will be removed in favor of a readme with links to their origin instead.
## Build Notes:
This toolhead might require other modifications to retain full functionality of your printer. 
 - Both test machines used for this mod had Rama's front idlers which have a much lower profile compared to stock Voron front idlers. The fan assemblies might conflict and reduce usable X travel.
 - The Klicky Probe carriage that was adapted was originally designed for the Dragon hotend. You'll need to use a taller probe body to reach the bed such as the one used by [Unklicky BFP](https://github.com/majarspeed/Unklicky). *This isn't an issue for Euclid or PCB Klicky*.
## Bill of Materials 
|Item|Count|Note|
|----|-|--|
|4010 24v blower fans|2|Add Polulu 3796 if you want the fancy 12v Deltas|
|3010 24v axial fan|1|
|M2x8 or M2x10 self-tapping|12|
|Rapido|1|
|m3x20 SHCS|2|
|m3x12 BHCS|2|
|m3x6 BHCS|6|
|6x3 magnets|3|
|Heatset|4|
|D2F-5L Microswitch|1|
|ZIP TIES||
|||
|**Optional**||
|**Nozzle LEDs**||
|SB nozzle LED kit or 2 of the spec RGB/RGBW LED chips||
|**Toolhead board**||
|HartK board v4 or CAN 36|
|Heatset|4|
|**Sensorized Mount**||
|D2F-5L Microswitch|1|
|M2x8 or M2x10 self-tapping|2|
|7mm Steel ball|1|
|**With Boots**||
|M2x20 SHCS|2|
|M2 Heatset Insert|2|https://www.amazon.com/gp/product/B08ZN4PS65|
## Changelog
### ?? September 2022 - Xol 2
- Improved aesthetics
- Downsized HE fan to 2520
- No more self-tapping screws
- Added front brace for Sherpa Mini
### 3 Aug 2022 - Xol with Boots
- Added MGN9H carriages for PCB Klicky
- Added additional stabilization for ducts. Ideally, these are fastened with 2x M2x20 and M2 heatset inserts.
![image](https://user-images.githubusercontent.com/86749712/182743176-836717be-50c4-4e77-87a8-01fd74bdcb33.png)

## Acknowledgement
[Long/Mandryd](https://github.com/mandryd/VoronUsers/tree/master/printer_mods/Long/Mantis_Dual_5015) for the Mantis toolhead.<br/>
[TheWarolf](https://github.com/TheWarolf/Voron-Personal-Mods/tree/main/V2/Long_Mantis_Toolhead) for the ERCF sensorized Hotend Mount.<br/>
[Derpimus](https://github.com/lraithel15133) for the exegesis, some CAD work, and feedback.<br/>
[KayosMaker](https://github.com/KayosMaker) for the MGN12 Klicky X-Carriage and CAN board mounts and spacers.<br/>
[JosAr](https://github.com/jlas1/Klicky-Probe) for Klicky.<br/>
[WhoppingPochard](https://github.com/tanaes) and [VinnyCordeiro](https://github.com/VinnyCordeiro/) for PCB Klicky.<br/>
[Nionio6915](https://github.com/nionio6915/Euclid_Probe) for Euclid. <br/>
[VoronDesign](https://github.com/VoronDesign) for this particular CoreXY flavor.<br/>
[AnnexEngineering](https://github.com/Annex-Engineering) for the Sherpa Mini and Double Folded Ascender extruders, and the K3 that influenced the air management of the ducts. And also for giving access to an early revision of the new DFA so it could be adapted for this toolhead.<br/>
[Clee](https://github.com/clee), you know what you did.
