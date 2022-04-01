# Specification

## Background

Speakup is a piece of hardware that will attach to a robust, mainstream tablet to amplify the sound from the tablet (so it can be heard in loud environments as a speech output device for people who use Augmentative and Alternative Communication. It will also allow two assistive technology switches to be attached that can be connected to the tablet and send characters to the device to facilitate assistive technology switch access.

## PCB/Electronic Requirements

  1. amplify sound input from tablet
  2. connect to tablet using Bluetooth
  3. volume to xdB TBC (equivalent to i13 https://www.tobiidynavox.com/products/i-series?tab=3)
  4. no lag or delay between input and output (for example for the Bluetooth device to 'wake')
  5. two switch inputs (see Switch Interface Wired project) using 3.5mm through hole jacks.
  6. PCB contained within a 50mm wide x 90mm wide rectangle so it is smaller than iPod Touch (58.6 x 123.4mm)
  7. USB-C connector on each short edge, centrally positioned.
  8. speaker unit to be 3W
  9. left channel volume control via button on long edge of device
  10. right channel volume control via buttons on long edge of device
  11. all connectors to be through hole so board can be supplied without these in place to wire in externally
  12. use one C Lithium battery, size will vary but connected using standard connector
  13. spare IO to header
  14. soft power switch
  15. jack connectors to be on short edge
  16. 4 off M3 mounting holes
  17. screen printed with project name "Speakup", url "https://acecent.re/eng", part number and revision number (610-006-A) and Ace Centre logo
  18. enable Speakup to act as a charger when connected to the host tablet via cable.
  19. enable Speakup to act as a keyboard (using the assistive technology switch inputs) when connected to the host tablet via cable
  20. sound channels programmable individually, left/right with independent volume control. QUERY/CONFIRM
  21. dip switches to assign characters to assistive technology switch inputs QUERY/CONFIRM

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
