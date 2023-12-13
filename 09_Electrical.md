# Electrical

Electrical panel is used to divert energy between all important devices

## Offsite lines

There are two offsite lines available:
- Line 826 - this line can be used to power the plant during startup and to send energy for profit
- Line 911 - this line can be used only as auxiliary for startup and during outages on Line 826, it won't accept power

## Buses

There are 3 buses:

- Main Bus - powers non critical equipment
- Safery Bus - powers critical equipment

Both of these buses can be connected either to one of the offsites or the generator. Safety bus can also be powered by diesel generator.

- Low Power Bus - powers devices such as lights or ventilation

This bus is powered from the Safety Bus or a battery

## Islanding mode

Islanding is a mode in which the plant powers itself. In order to go into islanding more, power production must be exactly matched with site power needs (so sent outside is 0). Next Line 826 breaker should be opened. Turbine will desync but will provide power to the buses. Depending on load changes RPM might change and it must be kept between 1450-1550. Whenever Line 826 is reconnected, generator will have to be synced to it again.
