<img src="https://github.com/Patsch91/NerdOCTAXE-Gamma/blob/feat_bm1370/Nerd0ctaxeGamma-Logo%20Big.png" width="250px">

**DoubleQ Rev2.2 **

Alternative PCB design to fit another cooler for an open PCB. 


<img src="https://github.com/Patsch91/NerdOCTAXE-Gamma/blob/LGA_Design-Rev-2.2/Images/20250408_185311.jpg" width="700px">

Highlights in comparison to the "standard" NerdOCTAXE:
- runs far more silent
- lower temps on asics and buck
- open PCB-design


The NerdOCTAXEγ runs with a modified version of the AxeOS: [ESP-Miner-NerdQAxe+](https://github.com/shufps/ESP-Miner-NerdQAxePlus) (Releases for NerdOCTAXE-Gamma)

-------------------------------

# Build

**DISCLAIMER:** This device is an *highly advanced* build and partly WIP. To get 8 Asics and the voltage regulator soldered properly *can* be very hard and frustrating if you are not used to soldering Asics or soldering in general. Using that amount of power, this device isn't a toy and you should know what you are doing - stay safe! Also this device is not intended or designed to run overclocked.

**PCB:** For example with the JLC Plugin for Kicad you can export the files out of Kicad to order directly from JLCPCB or any other PCB-Manufacturer. I tested my prototype with 1oz on inner and outer layers... working nice :) If anyone is testing or 2/1oz please let me know of the results you are seeing!

**BOM:** You can directly upload the .csv in this repo to Digikey. You will have to order the Lilygo T-Display S3 and the XT60PW-M seperately 

**HEATSINKS:** For this build I used two Thermalright AXP90-X53. For cooling the CSDs I "tinkered" on a custom heatsink with a 150x10mm aluminum rod and some fins, which I cut off another heatsink :) But its possible to just use 4x smaller heatsink directly on the CSDs

<img src="https://github.com/Patsch91/NerdOCTAXE-Gamma/blob/LGA_Design-Rev-2.2/Images/20250406_103209.jpg" width="800px">





Misc
====
If you like this project and want to support future work, feel free to donate to:
**`bc1q0ctaxeha3lpsaaz7kpjulflw2d9p66fhkp48dk`**


or related projects without which this project would not have been possible for me:

[Nerdaxe](https://github.com/BitMaker-hub/NerdAxeUltra)

[NerdQAxe+](https://github.com/shufps/qaxe)

[OSMU](https://osmu.wiki/)
