# Reactor Cooling

This is the main panel for the primary cooling circuit. Reactor Coolant Pumps will circulate water between the core and the steam generators, transferring heat between the primary (tube) side and the secondary (shell) side.
There are two legs in the system (left leg leading to left SG and right one leading to right SG), each having 2 pumps (RCP1 and RCP3 for the left leg, RCP2, RCP4 for the right leg).
Each leg of the system is divided into 2 parts, the hot leg (between the core and SG) and the cold leg (between SG and the core, where RCPs are located).

The right part of the panel has the autocontrol, which allows you to maintain a predefined hot leg temperature in each side (left/right).

Some PWRs rely on constant RPM pumps, where the temperature in the core depends on reactor power (the higher power, the higher temperature). We decided to implement variable RPM pumps which allow keeping constant temperature in the core as this is generally more efficient and allows you to experiment on how systems interact between each other.
