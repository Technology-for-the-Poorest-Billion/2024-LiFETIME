# Explanatory Notes

- 1st tests in July were not temp-controlled.
-  2nd and 3rd tests were temp-controlled.
#### Naming Scheme
(Battery Model)(ID)\_(Test Date)\_(Test Type)
###### Battery Models
-  SG = Samsung ICR18650-26J (2.6Ah, 3.63V, Li-Co)
-  RS = RS Pro LiFePO4 (1.5Ah, 3.2V, LiFePO4)
-  NX = Enix LiFePO4 (1.8Ah, 3.2V, LiFePO4)
###### ID is a unique numerical identifier.
###### Test Date [Day]-[Month]
Tests took place during July, August '23 and Jan '24. *This means that the tests occuring in Jan. occurred after the July and August tests.* This isn't immediately obvious without assessing the capacity degradation of the cells. Between August and January, the cells were stored in a dry container.
#### Cycling Data
Parameters measured:
1. Time
2. Cell Potential (V)
3. Current (mA)
4. Temperature
5. Cycle #

Cycle start is defined by the start of cell discharge.
Current with the convention that +ve is *into* the cell.
##### Expected Results:
RS is nominal 1.5Ah
NX is nominal 1.8Ah
SG is nominal 
##### Valid Cell Tests:
NX001 (Negligible Ah degradation over 250+ cycles, voltage drops around cycle 210)
- July has 87 cycles.
- August has 169 cycles.
- Charging procedure was changed between tests. Does not affect capacity results.
NX002 (Negligible Ah degradation over 250+ cycles, voltage drops around cycle 210)
- The same change in charging procedure is observed.
- July has 88 cycles.
- August has 171 cycles.
RS001 <50mAh degradation over 250+ cycles. Temperature had more influence than degradation.

RS006 <50mAh degradation over 250+ cycles. Temperature had more influence than degradation.

SG003

SG004

SG007 (3 tests) -> Degrades from 2.6Ah to 1.2Ah (46% SoH) over 396 cycles. 9.4Wh to 3.6Wh (38% SoH) -> Indicates voltage sag.

SG008

SG009 (3 tests) -> Degrades from 2.6Ah to 1.8Ah over 362 cycles (69% SoH). 9.3Wh to 6Wh (64.5% SoH) -> Indicates voltage sag.

##### Invalid Cell Tests:
NX006
- Something unusual happens in the final 2 cycles that confuses the capacity alogrithm.

#### EIS Data
EIS tests were performed at 33% and 66% charge at various points along the cycling tests.
The EIS did change within a cycle depending on the SoC at the time of the test.
