# Reactor Control

Reactor panel is located on the left side of the control room. It consists of the main panel and two supporting panels (CVCS and RHR).

## Reactor Panel

Reactor panel consist of the main reactor control switches (for the control rods) and secondary control switch (for the boric acid). Following switches are available:

On the left part:
- ROD MOV (rod movement) - allows to manually withdraw or insert the control rods
- MOVE SPD (movement speed) - allows to change how quickly rods move (slow/medium/fast)
- MODE SEL (mode selector) - allows to pull all rods at once (ALL) or single, selectable groups of rods (GROUP)
- AUTO BLNC (automaric balancer) - automatically balances power output between individual groups of rods
- AUTO MODE (autocontrol mode) - allows to chose whether autocontrol should use rods or boric acid injection
- BORIC ACID (boric acid) - allows to manually inject boric acid into the core or dilute with water

On the middle part:
The middle part allows to select individual groups of rods or their banks. A 2-d diagram of group rods is provided although it is not realistic for a PWR plant we decided to provide it so the player knows exact position of selected rod. Also whole banks (sets of 4 groups) can be selected. There is also a switch for startup and run mode.

On the right part:
- ROD LEVEL - this is a selector and indicator for Vertical Rod Display. It is possible to see one of 10 vertical slices of the core, or power averaged throut all levels
- IPR CTRL/LEVEL - this is a selector for the IPR mode (refer to startup)
- SETPOINT - power setpoint selector for the autocontrol, there are also buttons for predefined powers

## CVCS

On the left side of the reactor panel there is CVCS panel which is used to recycle used boric acid. The system consists of a water tank, boron concentrate tank, external tank and evaporator. Whenever water or boric acid is injected into the core, same amout of water from the core is moved into the external tank. This water will consist of some boric acid (depending on concentration), which can be recycled.

- XFR EVAP (transfer to evaporator) - transfers water from the external tank into evaporator
- EVAP HEAT (evaporator heater) - heats up the evaporator using live steam from the secondary system, water will boil in evaporator changing into steam, while remaining boric acid will stay at the bottom
- STEAM OUT - reliefs the steam from evaporator to condenser (not simulated) and back to water tank
- CONC OUT - when all water evaporated moves remaining boric acid back to boric acid tank

## RHR

Residual Heat Removal panel is on the far left side. At this moment only RHR mode is simulated. RHR will cool down left/right parts of the core during shutdown if pressure is below 3MPa.
