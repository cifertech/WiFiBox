<div align="center">

  <img src="https://user-images.githubusercontent.com/62047147/195847997-97553030-3b79-4643-9f2c-1f04bba6b989.png" alt="logo" width="100" height="auto" />
  <h1>WiFiBox</h1>
   
  <p>
    Packet Monitor with Waterfall Plot 
  </p>
   

 
<!-- Badges -->

<a href="https://github.com/cifertech/WiFiBox" title="Go to GitHub repo"><img src="https://img.shields.io/static/v1?label=cifertech&message=WiFiBox&color=purple&logo=github" alt="cifertech - WiFiBox"></a>
<a href="https://github.com/cifertech/WiFiBox"><img src="https://img.shields.io/github/stars/cifertech/WiFiBox?style=social" alt="stars - WiFiBox"></a>
<a href="https://github.com/cifertech/WiFiBox"><img src="https://img.shields.io/github/forks/cifertech/WiFiBox?style=social" alt="forks - WiFiBox"></a>
   
<h4>
    <a href="https://twitter.com/cifertech1">TWITTER</a>
  <span> · </span>
    <a href="https://www.instagram.com/cifertech/">INSTAGRAM</a>
  <span> · </span>
    <a href="https://www.youtube.com/c/cifertech">YOUTUBE</a>
  <span> · </span>
    <a href="https://cifertech.net/">WEBSITE</a>
  </h4>
</div> 
 
<br />

<!-- Table of Contents -->
# :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
  * [Pictures](#camera-Pictures)
  * [Features](#dart-features)
- [Getting Started](#toolbox-getting-started)
  * [Schematic](#electric_plug-Schematic)
  * [Installation](#gear-installation)
- [Usage](#eyes-usage)
- [Contributing](#wave-contributing)
- [License](#warning-license)
- [Contact](#handshake-contact)

  

<!-- About the Project -->
## :star2: About the Project
The traffic values in the channel specified from 1 to 14 are received and displayed with the help of ESP32, and TFT Lcd. graphically in the form of incoming traffic at any time will show with Waterfall Plot.

<!-- Pictures -->
### :camera: Pictures

<div align="center"> 
  <img src="https://user-images.githubusercontent.com/62047147/196050256-2fba0b5d-687d-44f7-a57d-353d09025fcf.jpg" alt="screenshot" width="Auto" height="700" />
</div>


<!-- Features -->
### :dart: Features

- Scan 2.4Ghz band
- Received Packets will show with Waterfall Plot.
- Ability to choose the desired channel from 14 channels

<!-- Getting Started -->
## 	:toolbox: Getting Started

We use st7735 Tft Lcd with ESP32. Also, I used a MicroSwitch in order to change 802.11 channels.

- TFT Lcd st7735
- ESP32
- Micro Switch

<!-- Schematic -->
### :electric_plug: Schematic
Make the connections according to the table and schematic below.

* ESP32 and st7735 tft LCD.

| ESP32 | TFT Lcd |  
| ----  | ----- |
| 14 | CS   |
| 33 | RST  |
| 27 | DC   |
| 18 | CLK  |
| 23 | DIN  |
| 5V | VCC  |
| 3V3 | LED |
| GND | GND |


* Arduino and Micro Switch.

| ESP32 | Micro Switch |
| ----  | -----|
| 22    | -    |

 
* Complete Schematic

<img src="https://user-images.githubusercontent.com/62047147/196051634-6a0f5314-96a1-4bf7-8b82-00e6b0c39f1e.png" alt="screenshot" width="800" height="auto" />


<!-- Installation -->
### :gear: Installation

Before uploading the code you need to install ESP32 in your Arduino IDE

- In Arduino IDE, go to File > Preferences
- Enter URLs Additional Boards Manager URLs field. Then, click the “OK”

```bash
  https://dl.espressif.com/dl/package_esp32_index.json
```

Then you need to install the required library in Arduino IDE. Follow these steps:

- Follow this path Sketch> Include Library> Manage Libraries
- Search for Adafruit_ST7735
- Install the library

<!-- Usage -->
## :eyes: Usage

After uploading the code, According to the channel selected by you, the packet monitor will display the received traffic.

  <img src="https://user-images.githubusercontent.com/62047147/196052554-8ea367b9-e4c7-4235-b819-b8d41b694d7c.png" alt="logo" width="300" height="auto" />



<!-- Contributing -->
## :wave: Contributing

<a href="https://github.com/cifertech/WiFiBox/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=cifertech/WiFiBox" />
</a>


<!-- License --> 
## :warning: License
 
Distributed under the MIT License. See LICENSE.txt for more information.


<!-- Contact -->
## :handshake: Contact 

CiferTech - [@twitter](https://twitter.com/cifertech1) - CiferTech@gmali.com

Project Link: [https://github.com/cifertech/WiFiBox](https://github.com/cifertech/WiFiBox)

<!-- Acknowledgments -->
## :gem: Acknowledgements 

 - [802.11 Mgmt:Beacon Frame](https://mrncciew.com/2014/10/08/802-11-mgmt-beacon-frame/)
 - [spacehuhn](https://github.com/spacehuhn)
 
 
