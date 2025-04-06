<img src="https://github.com/Patsch91/NerdOCTAXE-Gamma/blob/feat_bm1370/Nerd0ctaxeGamma-Logo%20Big.png" width="250px">

**BRANCH: LGA_Design**

Alternative PCB design to fit another cooler for an open PCB. 


<img src="https://github.com/Patsch91/NerdOCTAXE-Gamma/blob/LGA_Design/Images/NerdOCTAXE-Gamma_DoubleQ.jpg" width="700px">

Highlights in comparison to the "standard" NerdOCTAXE:
- runs far more silent
- lower temps on asics and buck
- open PCB-design


The NerdOCTAXEγ runs with a modified version of the AxeOS: [ESP-Miner-NerdQAxe+](https://github.com/shufps/ESP-Miner-NerdQAxePlus) (Releases for NerdOCTAXE-Gamma)

-------------------------------

# Build

**DISCLAIMER:** This device is an *highly advanced* build and partly WIP. To get 8 Asics and the voltage regulator soldered properly *can* be very hard and frustrating if you are not used to soldering Asics or soldering in general. Using that amount of power, this device isn't a toy and you should know what you are doing - stay safe!

**PCB:** For example with the JLC Plugin for Kicad you can export the files out of Kicad to order directly from JLCPCB or any other PCB-Manufacturer. I ordered 1oz on inner and outer layers and its working well for several weeks now. Happy to hear some feedback on 2/1oz or even 2/2oz boards (2/2oz would be incredibly hard to solder though)

**BOM:** You can directly upload the .csv in this repo to Digikey. You will have to order the Lilygo T-Display S3 and the XT60PW-M Power Connector seperately 

**HEATSINKS:** For this build I used two Thermalright AXP90-X53. For cooling the CSDs you have to use some kind of heatsinks otherwise they will overheat ... in the picture of the board above I used some small heatsinks directly on each Mosfet and on the Inductors to cool them. (WIP)

<img src="https://github.com/Patsch91/NerdOCTAXE-Gamma/blob/LGA_Design/Images/NerdOCTAXE-Gamma_DoubleQ%20PCB.jpg" width="800px">





Misc
====
If you like this project and want to support future work, feel free to donate to:
**`bc1q0ctaxeha3lpsaaz7kpjulflw2d9p66fhkp48dk`**


or related projects without which this project would not have been possible for me:

[Nerdaxe](https://github.com/BitMaker-hub/NerdAxeUltra)

[NerdQAxe+](https://github.com/shufps/qaxe)

[OSMU](https://osmu.wiki/)
