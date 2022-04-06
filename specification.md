# Specification

## Background

Speakup is a piece of hardware that will attach to a robust, mainstream tablet to amplify the sound from the tablet (so it can be heard in loud environments as a speech output device for people who use Augmentative and Alternative Communication. It will also allow two assistive technology switches to be attached that can be connected to the tablet and send characters to the device to facilitate assistive technology switch access.

## PCB/Electronic Requirements

  1. amplify sound input from tablet
  2. connect to tablet using Bluetooth
  4. no lag or delay between input and output (for example for the Bluetooth device to 'wake')
  5. two switch inputs (see Switch Interface Wired project) using 3.5mm through hole jacks.
  6. PCB contained within a 60mm wide x 90mm wide rectangle
  8. speaker output to be 5W per channel
  9. connections positioned as per dxf file
  10. Volume control on each of two channels to be controlled by an 'Up' and 'Down' tactile button
  11. all connectors to be through hole so board can be supplied without these in place to wire in externally
  12. use one C Lithium battery, size will vary but connected using standard connector
  13. spare IO to be routed through Adafruit Feather format header
  14. soft power switch
  16. mounting holes positioned as per dxf file
  17. screen printed with project name "Speakup", url "https://acecent.re/eng", part number and revision number (610-006-A) and Ace Centre logo
  18. enable Speakup to act as a charger when connected to the host tablet via cable.
  19. enable Speakup to act as a keyboard (using the assistive technology switch inputs) when connected to the host tablet via cable
  20. two 3.5mm jack headphone jack sockets. Socket 1 will output one channel to the headphone and one channel to the speaker when headphone connected. Socket 2 will output both channels when headphone connected. When headphones not connected, both channels directed to speakers
  21. One USB-C socket to be used to charge Speakup battery
  22. One USB-C socket used to charge host device only when Speakup connected to external power source
  23. All external connectors to be through hole
  24. User Feather footprint https://learn.adafruit.com/adafruit-feather/feather-specification

### PCB Notes

  - board likely to use ESP32 device nominally 25 x 20mm similar to that used on the Feather ESP32 https://www.adafruit.com/product/3405. Antenna is on short edge and needs to be positioned, no circuitry under board.
  - we're using this jack in our other boards https://uk.rs-online.com/web/p/jack-plugs-sockets/1248885

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

### Audio Configuration

![Tux, the Linux mascot](/assets/audio-config.png)

## Timescales

W/C 11/04/2022 PCB development start (3 days)
W/C 18/04/2022 Order PCB and components for self-assembly, 2 off sample boards
W/C 02/05/2022 Assemble sample boards (0.5 days)
W/C 09/05/2022 Order initial production
W/C 06/05/2022 Test first batch and assemble

