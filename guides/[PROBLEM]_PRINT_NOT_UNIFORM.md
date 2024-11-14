### PRINT QUALITY NOT HOMOGENOUS, BUT VARIES ACROSS THE PRINT BED

#### [BACK TO LIST OF ISSUES](../ENCOUNTERED_ISSUES.md)

*Updated 141124*
- Solved? `PARTIALLY`
- Encountered on: `n4pr` `n4+` `e5+`
- Suspected causes: `gantry` `bed`
- Prescriptions: `bed leveling` `gantry leveling` `bed cleaning` `rail cleaning`

#### Diagnosis:
Printing goes fine until it reaches certain areas or zones on the print bed, within which the filament can either NOT stick on the bed, or NOT coming out at all.

#### Causes and Solutions:
***TLDR:*** Check bed leveled?, check gantry leveled?, clean bed with alcohol, else print slower, else lower Z-offset and increase flow rate, else increase bed temp, else use different Curas.

When this happens, it tends to trace back to the fact that either the bed it not leveled properly, or the gantry is slanted, making the nozzle's trajectory across the bed a non-horizontal path. In this case, the mechanical configuration of the printer is at fault. Make sure to level the bed properly, as well as check if the nozzle gantry is as close to being parallel to the printer's base as possible. There have been tons of online guides on both leveling your heat bed and gantry, do check them out, or find [my own written guide](guides/[GUIDE]_BED_GANTRY_LEVELING.md) for this. What I suggest, however, is that you take all of them as reference, and designate your own way of calibrating the mechanical properties of the machine.

#### [BACK TO LIST OF ISSUES](../ENCOUNTERED_ISSUES.md)