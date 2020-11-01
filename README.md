# x-touch-mini-pi
Put a Raspberry Pi Zero W inside a Behringer X-Touch Mini and implement Xctl/MC/HUI over wifi

# Project Goals:
* Given a Behringer X-Touch Mini
* Mount a Raspberry Pi Zero W, battery and charging circuit inside
* alternatively, make a box that attaches to the side or bottom of the X-Touch Mini
* if possible, no case modifications should be made
* soldering to the X-Touch Mini PCB should be limited to the USB port
* In normal use, the USB port should only be required for charging and emergency programming
* The battery(s) should be rechargable and last at least 4 hours
* To th extent feasible, all Xctl functions should be implemented
* Custom button chords should be recognized where needed to provide direct access to functions
* an overlay should be created to document functions
* button and encoder lights should be used to give as much feedback as possible


# Phase 1 - Initial Proofs of Concept
* without modifying the X-Touch Mini, develop initial proof of concept on the Pi Zero hardware
* prove whether a Pi Zero W, battery(s) and charging circuit can fit inside the case without modification
* alternatively, design exterior case/attachment
* prove that the Pi Zero can power and communicate bidirectionally with the X-Touch Mini
* prove that the Pi Zero can communicate bidirectionally with a target device (X-Air mixer, DAW)

# Phase 2 - Build The Hardware
# Phase 3 - Complete Integrations with various target devices/software
