# TKLed - Untested
Stacked acrylic handwired 12.75u 40% keyboard with a push button and LED grid.

<img src="https://github.com/ElKinoflop/TKLed/blob/main/images/TKLed_v2_2025-Feb-05_11-35-57PM-000_CustomizedView7111979642.png" alt="TKLed Render">

Feel free to do whatever you want with the files. If you have any questions just ask (Discord username elkinoflop) and if you make one then share a photo with me!

<h1>Inspiration</h1>
<ul>
  <li>snurrebassen's <a href="https://geekhack.org/index.php?topic=101525.0">Arrow40</a></li>
  <li><a href="https://p3dstore.notion.site/P3Dstore-Open-Source-Project-List-6e85900337294e769fb7b8fa68d68f27">Jake/P3D's acrylic cases</a></li>
  <li><a href="https://smkeyboards.com/">SM Keyboards' acrylic cases</a></li>
</ul>

<h1>Layout</h1>
<img src="https://github.com/ElKinoflop/TKLed/blob/main/images/TKLed%20KLE.jpg" alt="TKLed Layout">

<h1>KLE Raw Data</h1>
["Esc","Q","W","E","R","T","Y","U","I","O","P",{w:1.5},"Back<br>Space",{x:0.25,a:7,w:3,h:1.5},""],
[{a:4,w:1.25},"Tab","A","S","D","F","G","H","J","K","L","@\n'",{w:1.25},"Enter"],
[{w:1.75},"Shift","Z","X","C","V","B","N","M","<\n.",">\n.",{w:1.75},"Shift",{x:1.25,a:7},""],
[{a:4,w:1.5},"Hyper",{x:1,w:1.5},"Meta",{a:7,w:2.25},"",{w:2.75},"",{a:4,w:1.25},"Meta",{x:1,w:1.25},"Super",{x:0.25,a:7},"","",""]

<h1>Case Manufacturing</h1>
<ul>
  <li><a href="https://github.com/ElKinoflop/Vozvan/tree/main/Case%20Files" target="_blank">Case files</a></li>
  <li>Designed to be cut from 3mm acrylic</li>
  <li>Note that acrylic sheets can vary in thickness even if they are listed as 3mm. I have found that Perspex® typically measures at 3-3.1mm whereas Xintao (which most Chinese suppliers seem to use) typically comes in at 2.6-2.7mm. This doesn't matter too much except for your switches will be much more visible with thinner sheets and it will be a tighter squeeze in the case for the wiring.</li>
  <li>Don't force the standoffs through if you find some of the standoffs too tight. Use a small round file if you need to slightly widen any holes. The small round file from Draper 'Soft Grip Needle File Set, 140mm (6 Piece) (83982)' is the perfect size. You shouldn't need to do this but there can be some manufacturing variance.</li>
</ul>

<h1>Bill of Materials</h1>
<ul>
  <li>One of each <a href="https://github.com/ElKinoflop/TKLed/tree/main/case%20files" target="_blank">case layer</a> cut from 3mm acrylic. You need two of the feet (unless you want a lower angle)</li>
  <li>Plate DXF file cut from 1.5mm metal/carbon. Flexier/plastic plates aren't recommened as without a PCB you can bottom out the switches on the case and risk the switches popping out of the plate</li>
  <li><a href="https://mechboards.co.uk/products/pro-micro-5v?_pos=2&_sid=c64ff0323&_ss=r" target="_blank">Pro Micro footprint RP2040 controller</a></li>
  <li>Sockets and pins to socket the controller</li>
  <li>M2 Standoffs with a outside diameter of 3mm. <a href="https://amzn.eu/d/8H1HG6Y" target="_blank">Amazon Standoffs</a></li></li>
  <li>M2 Hex socket button head bolts. Various lengths between 4-12mm. <a href="https://www.aliexpress.com/item/32969042589.html" target="_blank">AliExpress bolts</a></li>
  <li><a href="https://www.adafruit.com/product/2884" target="_blank">FeatherWing Proto board</a></li>
  <li>Adhesive gasket material. 4mm width. I used 2mm thickn gaskets but slightly thinner would be better.</li>
  <li>Wire! Solid core 22 AWG suggested</li>
  <li>45x MX Switches</li>
  <li>45x 1N4148 Diodes (plus any extras if you have buttons/encoders in the middle)</li>
  <li>4x small adhesive feet</li>
  <li>Right angle USB C adapter. <a href="https://www.amazon.co.uk/dp/B0CPLNH1L2?ref=ppx_yo2ov_dt_b_fed_asin_title" target="_blank">Amazon right angle USB C adapter</a></li>
  <li><a href="https://www.adafruit.com/product/2945" target="_blank">Adafruit NeoPixel FeatherWing</a></li>
  <li><a href="https://www.aliexpress.com/item/1005004920346156.html" target="_blank">16mm momentary push button</a></li>
</ul>

<h1>Firmware WIP</h1>

<h1>Controller Assembly</h1>
The controller, FeatherWing Proto and NeoPixel FeatherWing need assembling as pictured. I would advise socketing the controller and the ground and control pins that go to the NeoPixel FeatherWing. You can't socket the 5v connection as the pins don't line up so I have connected those with a short length of wire. The trace circled red needs cutting so the controller pins aren't shorted . The pads circled green need bridging with solder so that pin can be used to control the LEDs.
<img src="https://github.com/ElKinoflop/TKLed/blob/main/images/Featherwing%20Assembly.jpg" alt="Controller Assembly">

<h1>Handwired Matrix WIP</h1>

<h1>Disclaimer</h1>
Currently untested. You are ordering at your own risk and there are no guarantees that you end up with a functional item. If you do notice any mistakes please contact me (Discord username elkinoflop) so I can fix them.
