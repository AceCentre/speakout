# Specification

## Background

Speakup is a piece of hardware that will attach to a robust, mainstream tablet to amplify the sound from the tablet (so it can be heard in loud environments as a speech output device for people who use Augmentative and Alternative Communication. It will also allow two assistive technology switches to be attached that can be connected to the tablet and send characters to the device to facilitate assistive technology switch access.

## PCB/Electronic Requirements

Refer to [PCB Layout below](https://github.com/AceCentre/speakup/blob/main/specification.md#pcb-layout).

1. amplify sound input from tablet and provide access to device
2. connect to tablet using Bluetooth
3. no lag or delay between input and output (for example for the Bluetooth device to 'wake')
4. two switch inputs using 3.5mm through hole jacks (SW1 and SW2) to send character to host device (typically SPACE and ENTER)
5. PCB contained within a 60mm wide x 90mm wide rectangle
6. speaker output 5W per channel
7. connections positioned as per dxf file, see PCB Notes below
8. volume control on each of two channels to be controlled by an 'Up' and 'Down' tactile button
9. all connectors to be through hole so board can be supplied without these in place and connectors located on secondary boards elsewhere within a larger enclosure
10. use one C Lithium battery, size will vary but connected using standard connector
11. spare IO to be routed through header to the Adafruit Feather specification, see PCB Notes below
12. soft power switch (PWR)
13. mounting holes positioned as per dxf file
14. screen printed with project name "Speakup", url "https://acecent.re/eng", part number and revision number (610-006-A) and Ace Centre logo
15. enable Speakup to act as a charger when connected to the host tablet via cable
16. enable Speakup to act as a keyboard or mouse (using the assistive technology switch inputs and addtional IO) when connected to the host tablet via cable
17. two 3.5mm jack headphone jack sockets. HEAD1 will output one channel to the headphones when connected and one channel to the speaker. HEAD2 will output both channels to the headphones when connected. When headphones not connected, output both channels to speakers
18. One USB-C socket (IN) to be used to charge Speakup battery
19. One USB-C socket (OUT) used to charge host device only when Speakup connected to external power source
20. Use Feather footprint https://learn.adafruit.com/adafruit-feather/feather-specification
21. Additional IO programmable using Arduino IDE

### PCB Notes

  - board likely to use ESP32 device nominally 25 x 20mm similar to that used on the Feather ESP32 https://www.adafruit.com/product/3405. Antenna is on short edge and needs to be positioned, no circuitry under board.
  - we're using this jack in our other boards https://uk.rs-online.com/web/p/jack-plugs-sockets/1248885
  - see pdf/dxf of proposed board layout https://github.com/AceCentre/speakup/tree/main/assets. Option 1 preferred as the required external connectors are all on one edge making placing within the enclosure easier. Board size has increased in size slightly to allow suufficient spacing between connectors and buttons.
  - HEAD1 and HEAD2 are located on the same side as volume control as there is a functional association of these controls
  - HEAD1, HEAD2, IN, SW1 and SW1 overhanging edge of board 1.6mm to allow for wall thickness of enclosure so will sit flush on the external face when in position.
  - jack connectors 11mm min between centreline to allow for diameter of plug
  - jack connectors 12mm from centreline of USB-C socket to allow sufficient space for plug
  - OUT connector can be flush to edge of board as this will only be connected within enclosure and not exposed to user

## Hardware Requirements

Speakup will require:

  1. mounting plate
  2. carry handle
  3. kick stand

There will be two Speakup enclosure configurations suitable for:

  1. mobile phone size device or iPod Touch
  2. tablet (including iPad mini, Microsoft Surface Pro Mini, Surface Pro, iPad and similarly sized Android tablets)

To be confirmed, but it is envisaged that:

  - when unit is mounted in iPod Touch or mobile phone, a single speaker will be used
  - on larger devices use two sepaker units will be used
  - two versions of the PCB will be manufactured, one with all the components attached, one with all but one of the USB-C connectors so those components can be positioned elsewhere on the device.

Target assembled PCB price £50.

## Additional Information

### PCB Layout

![PCB layout](/assets/pcb-layout.png)

Option 1 preferred.

### Audio Configuration

![Audio confirguration diagram](/assets/audio-config.png)

## Timescales

W/C 11/04/2022 PCB development start (3 days)
W/C 18/04/2022 Order PCB and components for self-assembly, 2 off sample boards
W/C 02/05/2022 Assemble sample boards (0.5 days)
W/C 09/05/2022 Order initial production
W/C 06/05/2022 Test first batch and assemble

