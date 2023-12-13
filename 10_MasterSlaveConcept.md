# Master-Slave concept strategy

PWR plant has some interestig effects. Let's summarize them here:

## Reactor feedback

Light water moderated reactor reactivity will depend on density of the moderator which in PWR is the coolant water. Therefore the higher the temperature in the core, the lower the reactivity. This natural phenomen is main safety effect which stabilises the core. If the power raises and core temperature raises, the reactivity will drop. On the other hand when power and temperature drops, the reactivity will raise. Reactor is therefore stable although it will tend to oscillate around optimal power like a pendulum.

## Primary circulation feedback

As flow in the primary system can be controlled, temperature of the core can be changed by just adjusting the RCPs. When the flow is higher, more cooling is provided and core temerature will drop. Reactor will feel this effect and will automatically raise power to reach previous temperature. Of course it works the same way in the other direction. If we reduce cooling, temperature will raise, reactivity will drop, again reducing temperature.

Contrary to the first believ, primary circuit flow alone can't be used to change reactor temperature in the long term as reactor will always react to the change. It can be however another mean to change the reactor power. If more cooling is provided reactor power would raise.

## Secondary circuit feedback

Secondary circuit takes power from the primary. The more flow in the primary and the higher primary temperature, the more steam production one may expect. However temperature in the secondary is mostly set by the pressure which affects boiling point. In other words the higher the pressure, the higher the water temperature will raise before it boils. As the secondary temperature affects heat exchange, pressure can changes can affect the whole process. This is where Mster/Slave concept arises.

## Turbine-Master/Reactor-Slave

While one might think that the logical way to operate the plant is to first set power of the reactor for a demand and then adjust all other systems to deal with this power it is not how a PWR works. In a BWR reactor the scheme would be exactly like that and we suggest training this concept in RBWR first. In PWR reactor the concept is reversed:

- Power output should be set by steam demand in the secondary first, and rest of the systems should self adjust.

Let's discuss how this works. Let's assume we have a reactor in a stable state with everything setup for a certain power production in the turbine. Now lets open the turbine valve more, requesting more steam and power. What happens?

As more steam is used in the secondary pressure will drop. This will lower the boiling point causing temperature in the secondary to drop. How will primary react? With lowering water temperature in the steam generators, the water in primary will be cooled more effectively. In other words more power will be given away. Temperature difference between hot and cold leg will raise and this is the direct indication of power exchange between systems. Cooler water will enter core.

How will reactor react? With cooler water entering the core reactivity will raise. With raising power, the hot leg will get hotter than before raising also the temperature in the cold leg. This will inevitably cause more steam generation in the secondary and the pressure would raise back. We can expect a new steady state which will cause the pressure to come back to previous value with just more steam flow and more power generation. Of course all systems would react similarily when demand is lowered.

## The pendulum

This is the theory. We should adjust steam demand and hope for all other systems to adjust. Unfortunately in reality all the systems work a bit like pendulums. If you change the state of balance, the pendulum will move in that direction, but won't stop there. It will overshoot and then swing back. Therefore even though we might have the correct steady state parameters for our new demand, all systems will swing forth and back. Reactivity will raise, temperature will raise, pressure will raise, this will raise temperature in the cold leg, which will kill reactivity, so temperature will drop same as stea generation etc.

Therefore operators will try to dampen these oscillation by for example artificually lowering reactivity when the reactor is about to shoot over it's staady state power, and then bring it back so it doesn't swing back. Manual operations of a PWR are much more difficult than a BWR because so many things depend on each other.
