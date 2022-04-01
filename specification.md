# Specification

## Background

Speakup is a piece of hardware that will attach to a robust, mainstream tablet to amplify the sound from the tablet (so it can be heard in a loud environments as a speech output device for people who use Augmentative and Alternative Communication. It will also allow two assistive technology switches to be attached that can be connected to the tablet and send characters to the device to facilitate assistive technology switch access.

## PCB/Electronic Requirements

  1. amplify sound input from tablet
  2. connect to tablet using Bluetooth
  3. volume to xdB TBC (equivalent to i13 https://www.tobiidynavox.com/products/i-series?tab=3)
  4. no lag or delay between input and output (for example for the Bluetooth device to 'wake')
  5. two switch input (see Switch Interface Wired project)
  6. USB-C connector on each short edge, centrally positioned.
  7. connect to host device via Bluetooth 
  8. two 3.5mm jack for assistive technology switch
  9. speaker unit to be 3W
  10. left channel volume control via button on long edge of device
  11. right channel volume control via buttons on long edge of device
  12. all connectors to be through hole so board can be supplied without these in place to wire in externally
  13. use one C Lithium battery, size will vary bu device connecting using standard connector
  14. spare IO to header
  15. soft power switch
  16. PCB contained within a 50mm wide x 90mm wide rectangle so it is smaller than iPod Touch (58.6 x 123.4mm)
  17. Jack connectors to be on opposite edge to 
  18. 4 off M3 mounting holes
  19. screen printed with project name "Speakup", url "https://acecent.re/eng", part number and revision number (610-006-A) and Ace Centre logo
  20. enable Speakup to act as a charger when connected to the host tablet via cable.
  21. enable Speakup to act as a keyboard (using the assistive technology switch inputs) when connected to the host tablet via cable

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
