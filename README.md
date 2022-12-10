This repository holds all our electrical and electronics designs.

Contains files for a main PCB and an actuation PCB.

The main PCB uses an STM32F103CC controller and provides for interfacing with various sensors. It also interacts with our actuation PCB by accepting the zero-crossing detection signal from the actuation PCB and sends back actuation commands to it.