
# Dbus interface API

**com.jci.vbs.diag**


## Methods

### SetFault\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fault\_ID** | *in* | *u* |  |
| **return\_value** | *out* | *u* |  |


### ClearSingleFault\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fault\_ID** | *in* | *u* |  |
| **return\_value** | *out* | *u* |  |


### GetFaultStatus\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fault\_ID\_List** | *in* | *(auy)* |  |
| **return\_value** | *out* | *u* |  |


### ReadCMUFaults\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *u* |  |


### ReadAVCFaults\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *u* |  |


### ClearFaults\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fault\_ID\_List** | *in* | *(auy)* |  |
| **return\_value** | *out* | *u* |  |


### ClearFaults\_HMIRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *u* |  |


### Routine\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **routineID** | *in* | *y* |  |
| **routine\_Param** | *in* | *q* |  |
| **return\_value** | *out* | *u* |  |


### Data\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dIDNo** | *in* | *y* |  |
| **return\_value** | *out* | *u* |  |


### GGDS\_Data\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **data\_response** | *in* | *(yay)* |  |
| **return\_value** | *out* | *u* |  |


### GGDS\_Routine\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **routine\_response** | *in* | *(uyy)* |  |
| **return\_value** | *out* | *u* |  |


### TestScreen\_Status\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **testScreenStatus** | *in* | *y* |  |
| **return\_value** | *out* | *u* |  |


### TAU\_Vehicle\_Info\_Data\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dIDNo** | *in* | *y* |  |
| **return\_value** | *out* | *u* |  |


### BLM\_Ready\_Vehicle\_Info\_Data\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *(yyyyyyyyyyyyyy)* |  |


### GenericMessage\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **signalRequest** | *in* | *u* |  |
| **return\_value** | *out* | *u* |  |


### PermanentDTCLog\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *u* |  |


### Send\_SXM\_ESN



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vbs\_SXM\_ESN** | *in* | *(ay)* |  |
| **return\_value** | *out* | *u* |  |



## Signals

### GetFaultStatus\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **faultStatus** | *in* | *(a(uy)y)* |  |


### ClearFault\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **clearFaultAck** | *in* | *(a(uy)y)* |  |


### Clear\_HMIResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **clearHMIResponse** | *in* | *(uyy)* |  |


### GetRoutineStatus\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **routineResponse** | *in* | *(uyy)* |  |


### GetData\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dIDResponse** | *in* | *(yay)* |  |


### GGDSData\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **gGDSDataRequest** | *in* | *y* |  |


### GGDSRoutine\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **gGDSRoutineRequest** | *in* | *y* |  |


### GetVehicleInfoData\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **data\_vehicle\_info** | *in* | *(yyyyyyyyyyyyyy)* |  |


### GetSystemFailureError\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **error\_id** | *in* | *y* |  |
| **error\_status** | *in* | *y* |  |


### GetTAUVehicleInfoData\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **data\_vehicle\_info\_tau** | *in* | *(yyyqyyuyy)* |  |


### Session\_Notification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionID** | *in* | *y* |  |


### Vip\_Reset\_Notification




### ReadPermanentDTCLog\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dtc\_log** | *in* | *(ay)* |  |


### ReadPermanentDTCLogCounter\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dtc\_log\_counter** | *in* | *(aqy)* |  |

