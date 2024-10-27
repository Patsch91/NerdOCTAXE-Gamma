<img src="https://github.com/Patsch91/NerdOCTAXE-Plus/blob/main/Nerd0ctaxe%2B-Logo%20green250.png" width="250px">

The NerdOCTAXEγ is a 8-Asic version of the [NerdQAxe++](https://github.com/shufps/qaxe) with [Nerdminer](https://github.com/BitMaker-hub/NerdMiner_v2) / [Nerdaxe](https://github.com/BitMaker-hub/NerdAxeUltra) Display and is running the [BitAxe](https://github.com/skot/bitaxe) Firmware as its Core.

It runs standalone and uses 8 ASICs of type BM1370 to achieve an average Hashrate of ~9-10Th/s at ~180Watts 


<img src="https://github.com/Patsch91/NerdOCTAXE-Gamma/blob/feat_bm1370/GammaFront.jpg" width="700px">

Highlights:

- uses the NerdAxe / NerdMiner display
- 3-Phase Buck  // The TPS could handle 4 Phases... currently thinking of changing it to 4-Phase design
- Standalone, no Raspberry Pi or other PC needed
- AxeOS with improvements and enhancements - slightly modified version of [ESP-Miner-NerdQAxe+](https://github.com/shufps/ESP-Miner-NerdQAxePlus)
  - Influx DB support
  - Better charting (10m, 1h, 1d), data doesn't get lost on Web UI reloads 
  - ASIC clock and voltage adjustable without reboot
  - Stratum client stability improvements (TCP timeouts)

The NerdOCTAXEγ runs with a modified version of the AxeOS: [ESP-Miner-NerdQAxe+](https://github.com/shufps/ESP-Miner-NerdQAxePlus) (Releases für NerdOCTAXE-Gamma)

-------------------------------

# Build

**DISCLAIMER:** This device is an *highly advanced* build and partly WIP. To get 8 Asics and the voltage regulator soldered properly *can* be very hard and frustrating if you are not used to soldering Asics or soldering in general. Using that amount of power, this device isn't a toy and you should know what you are doing - stay safe!

**PCB:** For example with the JLC Plugin for Kicad you can export the files out of Kicad to order directly from JLCPCB or any other PCB-Manufacturer

**BOM:** You can directly upload the .csv in this repo to Digikey (watch out - this is still a bit of WIP - you could delete the heatsink for example, which is actually in the BOM, but I am currently testing other ones which I will add later on). You will have to order the Lilygo T-Display S3 seperately.

**HEATSINKS:** Cooling is always a bit WIP. For the Asics I used the Heatsinks of "Fujitsu Primergy RX2540 M1 M2" 

**FANS:**  2x Arctic S8038-7K (Monsters :P).  I am currently running this miner with Fan-PWM set to 55%. This is enough to keep the buck at about 60°C and asics ~60-70°C (Heatsink Temp displayed on the UI about 40°C) . (!!Note: These Fans have a relatively high "starting current" - so make sure you dont change the fan-pwm upwards in steps too big... for example the miner running hot with Fan-PWM at ~10% (pulling more amps as the Asics getting hot) turning the Fan-PWM up to 90% in one step *could* lead to triggering the Fuse as the fans are pulling heavy to "accelerate")

<img src="https://github.com/Patsch91/NerdOCTAXE-Gamma/blob/feat_bm1370/GammaOpen.jpg" width="800px">

**CASE** I used a 80x160mm Aluminium-Case which can be found in various lengths on Amazon/ebay/aliexpress etc.

**BACKPLATE** Step files will be provided soon. Will make some changes to integrate the T-Display better into the Backplate :) I used these [XT60 Terminals](https://www.amazon.de/VUNIVERSUM-XT60BE-F-Einbaustecker-Wassergesch%C3%BCtzt-Goldstecker/dp/B0BY5SSBNL/ref=sr_1_1?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=34SJX8BBY8ON9&dib=eyJ2IjoiMSJ9.1gWRfzyjYg4bochdDJrZlRVYumEdfbuNmB9-tGHzJcIb43ml4XVsd7a3uDXD2iBPC0VDiEgHDlwWwVkF-92e74IFhp-S4UWtzd6yQ47CHllmSU8KjdiRrpzJARoorImGF0pPt3yHRGvtf1Ozm4UyCUMyZ6IReK-jElBGeGyKX8cTt_2FxpvnRJDy0r_NakaZLaCqHOmzsKAQ0OkySNdaHGHs4863GlvpFFscyhVBi2-jv66gvIWAMFURS7OmJllvcU08Q1x8cLdpYHryuXGPbBDmlPvm5ogLmzHkYKdlI_g.x6tgIGdrJyV-OXpLUBDueyoo4Cg18nlT5IFb1QiYruQ&dib_tag=se&keywords=vuniversum%2Bxt60be&qid=1725552322&sprefix=vuniversum%2Bxt60be%2Caps%2C89&sr=8-1&th=1=) integrated in the Backplate.


-------------------------------

Current developments:
====
10/14/24: Changed the 4-Layer PCB to 6-Layer to conquer the heavy load on the rather small 1V2-Zone and added a whole 1V2 Layer + GND Layer. This should reduce the PCB-Temperatures, the Buck Temperature as it is located near the "hot" area and the voltage drop between the buck and the Asic Input. This design should be a little more energy efficient - I guess just some %´s, but should be noticable. 



Misc
====
If you like this project and want to support future work, feel free to donate to:
**`bc1q0ctaxeha3lpsaaz7kpjulflw2d9p66fhkp48dk`**


or related projects without which this project would not have been possible for me:

[Nerdaxe](https://github.com/BitMaker-hub/NerdAxeUltra)

[NerdQAxe+](https://github.com/shufps/qaxe)

[OSMU](https://osmu.wiki/)
