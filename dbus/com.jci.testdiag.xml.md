
# Dbus interface API

**com.jci.testdiag**


## Methods

### StartRoutine



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **test\_id** | *in* | *y* |  |
| **return\_value** | *out* | *i* |  |


### ActivateTestMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### DeactivateTestMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### CommanderInput



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **buttont\_id** | *in* | *n* |  |
| **buttont\_value** | *in* | *n* |  |
| **return\_value** | *out* | *i* |  |


### StopCommanderRoutine



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetTestInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **testInfo** | *out* | *(ua(uay))* |  |


### ActivateJCITestMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### DeactivateJCITestModeMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### NotifyDiagLostFocus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetDiagStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *out* | *u* |  |



## Signals

### TestRoutineStatus\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **test\_status** | *in* | *s* |  |
| **test\_info** | *in* | *(uay)* |  |
| **response\_data** | *in* | *(iay)* |  |
| **gui\_state** | *in* | *(b(ay)(bbb(bay)))* |  |
| **isTUIDataReq** | *in* | *b* |  |
| **endOfData** | *in* | *b* |  |


### NotifyTestMode\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **test\_mode** | *in* | *u* |  |


### SystemError\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **error\_id** | *in* | *u* |  |
| **error\_status** | *in* | *u* |  |


### DVD\_SpeedRestriction\_Enable



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **speed\_Restriction\_Enable** | *in* | *b* |  |

