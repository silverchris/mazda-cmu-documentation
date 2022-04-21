
# Dbus interface API

**com.jci.vbs.bcm**


## Methods

### GetCarSpeed



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **speedUnit** | *in* | *u* |  |
| **return\_vehicleSpeed** | *out* | *u* |  |


### GetCarSpeedThrshld



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **speedUnit** | *in* | *y* |  |
| **return\_carSpeedThrshld** | *out* | *y* |  |


### GetPSMInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### GetBSMInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **bsmInformation** | *out* | *(bbyyybbbbbbyy)* |  |


### getEngineTransmissionType



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **returnTransmissionType** | *out* | *y* |  |


### GetIgnitionStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_ignitionStatus** | *out* | *y* |  |


### GetPublicCanStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_PublicCanStatus** | *out* | *y* |  |


### GetPrivateCanStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_PrivateCanStatus** | *out* | *y* |  |


### GetNoSpeedRestrict\_TouchDisplay



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_noSpeedRestrict** | *out* | *y* |  |


### GetTouchDisplayCarSpeedThrshld



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **speedUnit** | *in* | *y* |  |
| **return\_touchDisplayCarSpeedThrshld** | *out* | *y* |  |


### GetFuelCutOffStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_FuelCutOff** | *out* | *y* |  |


### GetBrkPedalDepressedStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_brkPdlDprssed** | *out* | *y* |  |


### GetGearPos



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_gearPos** | *out* | *y* |  |


### GetTransmChangeLeverPosition



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_transmChangeLeverPos** | *out* | *y* |  |


### GetPrkBrkActv



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_prkBrkActv** | *out* | *y* |  |


### GetPASCD



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pascdInformation** | *out* | *(ay)* |  |


### GetWheelSpeed



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **wsInformation** | *out* | *(qqqqqqt)* |  |


### GetVideoRestrict



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_videoRestrict** | *out* | *y* |  |



## Signals

### CarSpeedResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **carSpeed** | *in* | *u* |  |


### CarSpeedThresholdNotification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **carSpeedThrshld** | *in* | *y* |  |


### AccidentTriggerNotifiction



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fuelCutOff** | *in* | *y* |  |


### PSM\_Information1



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **psInformation** | *in* | *(yyyyyyyyyy)* |  |


### BSM\_Information



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **bsmInformation** | ** | *(bbyyybbbbbbyy)* |  |


### PublicCanStatusNotification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **publicCanStat** | *in* | *y* |  |


### PrivateCanStatusNotification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **privateCanStat** | *in* | *y* |  |


### engineConfigResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **engineConfigType** | *in* | *y* |  |
| **engineConfigValue** | *in* | *(y)* |  |


### IgnitionControl\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ignitionControl** | *in* | *y* |  |


### NoSpeedRestrict\_TouchDisplay



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **noSpeedRestrict** | *in* | *y* |  |


### BatteryVoltageFlag



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **batt\_volt\_flag** | *in* | *b* |  |


### BrakePedalDepressedStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **brkPedalDepressed** | *in* | *y* |  |


### GearPosNotification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **gearPos** | *in* | *y* |  |


### TransmChangeLeverPositionNotification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **transmChangeLeverPos** | *in* | *y* |  |


### PrkBrkActvNotification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **prkBrkActv** | *in* | *y* |  |


### PASCDNotification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pascdInformation** | ** | *(ay)* |  |


### WheelSpeedNotification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **wsInformation** | ** | *(qqqqqqt)* |  |


### VideoRestrictNotification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **videoRestrict** | *in* | *y* |  |

