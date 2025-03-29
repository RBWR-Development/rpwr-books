# Dispatching room

The dispatching room is a first try at implementing a mechanics which would allow to simulate a whole electrical network where RPWR is just one part of it. The goal of the dispatching minigame is to meet all power demands without overpowering the network while dealing with malfunctions and closures.

## Power sources

Green boxes are your power sources. Some of them can be adjusted with a separate screen (it takes time for power sources to change output), some (like the renewables) cannot be controlled although their production prediction for 24 hours is available. Sometimes a power source will go down for maintenance. In that case additional number appears which indicates number of ingame minutes before it goes down. RPWR remains player controlled but power demand can be still selected which will be passed to the control room.

## Demands

Blue boxe are demands and the numbers indicate power recieved/power demand. Meet the demands to earn points in the game. There is a 24h forecast for all demands available.

## Storage

Pumped storage is a facility which can store energy. Depending on selection in can be used as a power source (while discharging) or a demand (charging).

## Power lines

Power lines transport energy. Green means eneabled, red disabled and yellow means it needs maintenance (additional number will indicate time until it goes down). To repair a line turn it off and call for maintenance. Each power line has maximum transmission limit and if you go over it you are risking a malfunction. Reconfiguring the network will cause electricity to self distribute like in real life (it is assumed all lines are the same voltage and resistance).

## Overcharged nodes

Whenever you produce more power that can be absorbed by the network some nodes will overcharge which will be indicated by blue indicators with ### instead of load. This is a very dangerous situation and it will eventually lead to tripping one of the power sources or the whole network can collapse. Never allow this to happen. It's better to stay just a little below than the demand than above. Plan ahead!
