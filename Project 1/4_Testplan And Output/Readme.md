# **TESTPLAN AND OUTPUT


## HIGH LEVEL TEST PLAN

|TestID|Description|Exp Input|Exp Output|Status|
|:-----|-----------|---------|----------|-----:|
|HL01|Remote Car Locking|switch pressed 1 time|Car Locked|Passing|
|HL02|Remote Car UnLocking|switch pressed 2 times |Car UnLocked|Passing|
|HL03|Alarm Activation|switch pressed 3 times|Alarm Activated|Passing|
|HL04|Alarm DeActivation|switch pressed 4 times|Alarm DeActivatedd|Passing|

## LOW LEVEL TEST PLAN

|TestID|Description|Exp Input|Exp Output|Status|
|:-----|-----------|---------|----------|-----:|
|LL01|All LEDs Should get turn ON together when Car is locked|switch pressed 1 time|All Leds are ON|Passing|
|LL02|All LEDs Should get turn OFF together when Car is unlocked|switch pressed 2 time|All Leds are OFF|Passing|
|LL03|Alarm Activation|switch pressed 3 times|LEDs turned ON one by one in clockwise direction|Passing|
|LL04|Alarm deactivation|switch pressed 4 time|LEDs turned OFF one by one in clockwise direction|Passing|

