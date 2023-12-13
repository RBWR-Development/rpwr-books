# Reactor Cooling

This is the main panel for the primary circuit. Reactor Coolant Pumps will circulate water between the core and the steam generators allowing for heat exchange between primary and secondary.
There are two legs of the system (left leg leading to left SG and right one leading to right SG), each having 2 pumps (RCP1 and RCP3 foe the left leg, RCP2, RCP4 for the right leg).
Each part of the system is dividen into the hot leg (between the core and SG) and cold leg (between SG and the core, where RCPs are located).

Right of the panel there is autocontrol, which allows to maintain a predefined hot leg temperature in each part (left/right).

Some PWRs rely on constant RPM pumps. In such a case temperature in the core depends on reactor power (the higher power, the higher temperature). We decided to implement variable RPM pumps which allow to keep constant temperature in the core as this is generally more efficient and allows more to experiment on how systems interact between each other.
