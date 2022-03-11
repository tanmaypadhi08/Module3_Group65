# Test Plan

## High Level Test:

|Test id |Description |expected i/p |expected o/p |Actuall o/p |pass/fail |            
|--------|------------|-------------|-------------|------------|----------|
| HLR1   |Car lock    |Lock button is pressed |locked |locked |pass ✅ |
| HLR2   |Car unlock |unlock button is pressed |unlock |unlock |pass ✅ |
| HLR3   |Alarm(Activation/Deactivation) |Activation/Deactivation button is pressed |Alarm(Activated/Deactivated) |Alarm(Activated/Deactivated) |pass ✅ |
| HLR4   |Approach Lights |the button is pressed |Approach lights ON |Approach lights ON |pass ✅ |
| HLR5   |Encryption|- |Pattern |Pattern |pass ✅|


## Low Level Test:


|Test id |Description |expected i/p |expected o/p |Actuall o/p |pass/fail |
|--------|------------|------------ |-------------|------------|----------|
|LLR1|test for car lock |Switch is pressed |All the led's are turned ON at same time  |All the led's are turned ON at same time |pass ✅ |  
|LLR2 |test for car Unlock |Switch is pressed Twice |All the led's are turned OFF at same time  |All the led's are turned OFF at same time |pass ✅ |  
|LLR3 |test for Alram (Activation/Deactivation) |Switch is pressed Thrice |All the led's are turned ON in clockwise direction  |All the led's are turned ON in clockwise direction  |pass ✅|  
|LLR4 |test for Approach Light|Switch is pressed 4 times |All the led's are turned ON in anticlockwise direction  |All the led's are turned ON in anticlockwise direction  |pass✅  |  
|LLT5 |test for Encryption|- |pattern  |pattern  |pass✅  | 
