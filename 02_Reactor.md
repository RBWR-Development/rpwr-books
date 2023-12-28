# Reactor Control

The reactor panel is located on the left side of the control room. It consists of the main panel and two supporting panels (CVCS and RHR).

## Reactor Panel

The reactor panel consists of the main reactor control switches (for the control rods) and secondary control switches (for the boric acid). The following switches are available:

On the left:
- ROD MOV (rod movement) - Allows to manually withdraw or insert the control rods.
- MOVE SPD (movement speed) - Allows changing how quickly rods move (slow/medium/fast).
- MODE SEL (mode selector) - Allows to pull all rods at once (ALL) or single, selectable groups of rods (GROUP).
- AUTO BLNC (automatic balancer) - Automatically balances power output between individual groups of rods.
- AUTO MODE (autocontrol mode) - Allows choosing whether autocontrol should use rods or boric acid injection.
- BORIC ACID (boric acid) - Allows to manually inject boric acid into the core or dilute with water.

On the middle:
The middle section allows you to select individual groups of rods or their banks. A 2-d diagram of the rod groups is provided although it is not realistic for a PWR plant, we decided to provide it so that the player knows  the exact position of any selected rod. Also whole banks (sets of 4 groups) can be selected. There is also a switch for startup and run mode.

On the right:
- ROD LEVEL - This is a selector and indicator for Vertical Rod Display. It is possible to see one of 10 vertical slices of the core, or power averaged through all levels.
- IPR CTRL/LEVEL - This is a selector for the IPR mode (refer to startup).
- SETPOINT - Power setpoint selector for the autocontrol, there are also buttons for predefined powers.

## CVCS

On the left side of the reactor panel there is CVCS panel which is used to recycle used boric acid. The system consists of a water tank, boron concentrate tank, external tank and evaporator. Whenever water or boric acid is injected into the core, the same amount of water from the core is moved into the external tank. This water will consist of some boric acid (depending on concentration), which can be recycled.

- XFR EVAP (Transfer to evaporator) - Transfers water from the external tank into evaporator.
- EVAP HEAT (Evaporator heater) - Heats up the evaporator using live steam from the secondary system, water will boil in evaporator changing into steam, while the remaining boric acid will stay at the bottom.
- STEAM OUT - Relieves the steam from the evaporator to the condenser (not simulated) and back to water tank.
- CONC OUT - When all water is evaporated, moves remaining boric acid back to boric acid tank.

## RHR

Residual Heat Removal panel is on the far left side. At this time only RHR mode is simulated. RHR will cool down left/right parts of the core during shutdown if pressure is below 3MPa.
