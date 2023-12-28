# Master-Slave concept 

PWR plants have some interesting effects and feedback loops, lets summarize them here:

## Reactor feedback

In a light water moderated reactor, the reactivity will depend on density of the water coolant. Therefore, the higher the temperature in the core, the lower the reactivity. This natural phenomenon is main safety effect which stabilizes the core. If the power raises and core temperature raises, the reactivity will drop. On the other hand when power and temperature drop, the reactivity will raise. The reactor is therefore stable although it will tend to oscillate around optimal power like a pendulum.

## Primary circulation feedback

As the flow in the primary system can be controlled, temperature of the core can be changed by just adjusting the RCPs. When the flow is higher, more cooling is provided and core temperature will drop. Reactor will feel this effect and will automatically raise power to reach previous temperature. Of course, it works the same way in the other direction. If we reduce cooling, temperature will raise, reactivity will drop, again reducing temperature.

Contrary to popular belief, primary circuit flow alone can't be used to change reactor temperature in the long term as reactor will always react to the change. It can be however another mean to change the reactor power. If more cooling is provided the reactor power would rise.

## Secondary circuit feedback

The secondary circuit takes power from the primary. The more flow in the primary and the higher the primary temperature, the more steam production one can expect. However, the temperature in the secondary is mostly set by the pressure which affects boiling point. In other words the higher the pressure, the higher the water temperature will rise before it boils. As the secondary temperature affects heat exchange, pressure changes can affect the whole process. This is where Master/Slave concept arises.

## Turbine-Master/Reactor-Slave

While you might think that the logical way to operate the plant is to first set power of the reactor for a demand and then adjust all other systems to deal with this power it is not how a PWR works. In a BWR reactor the scheme would be exactly like that, and we suggest training this concept in RBWR first. In a PWR reactor the concept is reversed:

- Power output should be set by steam demand in the secondary first, and rest of the systems should self adjust.

Let's discuss how this works. Let's assume we have a reactor in a stable state with everything setup for a certain power production in the turbine. Now lets open the turbine valve more, requesting more steam and power. What happens?

As more steam is used in the secondary pressure will drop. This will lower the boiling point causing temperature in the secondary to drop. How will primary react? With lowering water temperature in the steam generators, the water in primary will be cooled more effectively. In other words more power will be given away. The temperature difference between hot and cold legs will rise and this is the direct indication of power exchange between systems. Cooler water will enter the core.

How will the reactor react? With cooler water entering the core reactivity will raise. As the power rises, the hot leg will get hotter than before raising also the temperature in the cold leg. This will inevitably cause more steam generation in the secondary and the pressure would raise back. We can expect a new steady state which will cause the pressure to come back to previous value with just more steam flow and more power generation. Of course all systems would react similarly when demand is lowered.

## The pendulum

This is the theory. We should adjust steam demand and hope for all other systems to adjust. However, in reality the systems work a bit like a pendulum. If you change the state of balance, the pendulum will move in that direction, but won't stop there. It will overshoot and then swing back. Therefore, even though we might have the correct steady state parameters for our new demand, all systems will swing forth and back. Reactivity will raise, temperature will raise, pressure will raise, this will raise temperature in the cold leg, which will kill reactivity, so temperature will drop same as steam generation etc.

Therefore, operators will try to dampen these oscillations by for example artificially lowering reactivity when the reactor is about to shoot over it's steady state power, and then bring it back so it doesn't swing back. Manual operation of a PWR is much more difficult than a BWR because so many things depend on each other. To make it even worse if one decides to enforce some parameters with autocontrol, the whole system may react differently than expected.
