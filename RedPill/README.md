# STM32 RedPill

</p>This is a custom STM BluePill type development board that houses the STM32F103C8T6 and can be programmed using the Arduino IDE via an FTDI type adpator or the included USB port. In order to succesfully program the board over serial, you need to flash the Arduino bootloader on the MCU using either the STM Flasher as covered in the following tutorial:</p>
https://www.youtube.com/watch?v=wGbiT6IxGP0<br>

</p>The gerber files can be sent to JLCPCB.com for manufacturing since they agree with their constraints and the components can be ordered via LCSC.com using the BOM provided.<br>
Soldering this PCB may come across as a bit of a challenge for some since it requires soldering a 48 pin LQFP package as well as a 3225 packaged crystal oscillator with pads on the bottom. Both of these are easily solderable if you have access to a hot air station, but definitely doable with a temperature controlled iron and a well tip.<br>
The BOM can be simply uploaded to LCSC using their BOM tool to add all required components directly to the cart. Note to be made here, header pins are not included in the BOM since I want to leave the choice of male/female up to the designer.</p>
&nbsp;&nbsp;&nbsp;&nbsp;Goals:
 <il>   

- Implement USB-C for future proofing.
- Utilize MCP1700-3302E 3.3V LDO
 <il>
 