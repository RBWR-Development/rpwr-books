# Electrical

The electrical panel is used to control breakers that power all devices in the plant.

## Offsite Lines

There are two offsite lines available:
- Line 826 - this line can be used to power the plant during startup and to send energy to the grid to meet demand
- Line 911 - this line can be used only as auxiliary for startup and during outages on Line 826, it won't accept power

## Buses

There are 3 buses:

- Main Bus, powers non critical equipment.
- Safety Bus, powers critical equipment.

Both of these buses can be connected either to one of the offsites or the generator. Safety bus can also be powered by diesel generator.

- Low Power Bus, powers devices such as lights, controls or ventilation.

This bus is powered from the Safety Bus or a battery

## Islanding mode

Islanding is a mode in which the plant powers itself. In order to go into islanding mode, the power production must be exactly matched with site power demand. Next Line 826 breaker should be opened. The turbine will desync but will still provide power to the buses. Depending on load changes RPM might change and it must be kept between 1450-1550. Whenever Line 826 is reconnected, the generator will have to be synced to it again.
