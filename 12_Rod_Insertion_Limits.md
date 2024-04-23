# Rod Insertion Limits
Rod Insertion Limits (RILs) are a safety feature in Pressurized Water Reactors that are used to ensure that the reactor will *always* go subcritical during a reactor trip.

Rod Insertion Limits exist for the four control banks (Bank 1, 4, 5, and 6) and are displayed on a monitor to the right of the reactor control panel.

To satisfy the conditions of the RILs, all four control rods in the bank must *always* be withdrawn higher than the RILs. To do this, more boric acid is added to the reactor coolant system, this ensures that the control rods can be raised while maintaining the same power level.
If the reactor trips, the extra boric acid along with the higher control rods ensure more negative reactivity insertion while the control rods are being dropped, which guarantees that the core goes subcritical during the trip.

There are two alarms that are used to alert the operator of excessive control rod insertion:
- **RIL Warning**: This alarm triggers if any control rod in the bank is withdrawn less than 2% above the RIL.
- **Rod Below Insertion limit**: This alarm triggers if any control rod in the bank is withdrawn less than the RIL.
Both of these alarms automatically get bypassed if all four control rods in the bank are withdrawn to 100%.
