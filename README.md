<img src="https://github.com/Patsch91/NerdOCTAXE-Gamma/blob/feat_bm1370/Nerd0ctaxeGamma-Logo%20Big.png" width="250px">

**NerdOCTAXE-γ Rev3.4  **



<img src="https://github.com/Patsch91/NerdOCTAXE-Gamma/blob/ph6/Images/Rev3-4.jpg" width="700px">

Rev3.4:
- 6 Phase Buck Converter
- Added curcuit to read the internal temperature of each asic



The NerdOCTAXEγ runs with a modified version of the AxeOS: [ESP-Miner-NerdQAxe+](https://github.com/shufps/ESP-Miner-NerdQAxePlus) (Releases for NerdOCTAXE-Gamma)

To flash the Lilygo T-Display you can use the [Webflasher](https://shufps.github.io/nerdqaxe-web-flasher/)

-------------------------------

# Build

**DISCLAIMER:** This device is an *highly advanced* build and partly WIP. To get 8 Asics and the voltage regulator soldered properly *can* be very hard and frustrating if you are not used to soldering Asics or soldering in general. Using that amount of power, this device isn't a toy and you should know what you are doing - stay safe! Also this device is not intended or designed to run overclocked.

**PCB:** For example with the JLC Plugin for Kicad you can export the files out of Kicad to order directly from JLCPCB or any other PCB-Manufacturer. I tested my prototype with 1oz on inner and outer layers... working nice :) If anyone is testing 2/1oz or 2/2oz please let me know of the results you are seeing!

**BOM:** You can directly upload the .csv in this repo to Digikey. You will have to order the Lilygo T-Display S3 and the XT60PW-M seperately 

**HEATSINKS:** For this build I used two Thermalright AXP90-X53 

**ASICS:** This board utilizes Bitmains BM1370-Series. I tested boards with the following variants: BM1370BC < BM1370PA < BM1370PF 







Misc
====
If you like this project and want to support future work, feel free to donate to:
**`bc1q0ctaxeha3lpsaaz7kpjulflw2d9p66fhkp48dk`**


or related projects without which this project would not have been possible for me:

[Nerdaxe](https://github.com/BitMaker-hub/NerdAxeUltra)

[NerdQAxe+](https://github.com/shufps/qaxe)

[OSMU](https://osmu.wiki/)
