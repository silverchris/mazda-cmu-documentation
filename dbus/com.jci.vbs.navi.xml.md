
# Dbus interface API

**com.jci.vbs.navi**


## Methods

### GetFuelType



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_fuelType** | *out* | *y* |  |


### GetHUDStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_HUDStatus** | *out* | *y* |  |


### GetTSRStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_TSRStatus** | *out* | *y* |  |


### GetTSRMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_TSRMode** | *out* | *y* |  |


### TMCServiceListReq



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tmcSrvceLstReq** | *in* | *y* |  |
| **return\_status** | *out* | *y* |  |


### TMCSelectReq



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tmcSelectReq** | *in* | *(yyyyy)* |  |
| **return\_status** | *out* | *y* |  |


### SetHUDDisplayMsgReq



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hudDisplayMsg** | *in* | *(uqyqyy)* |  |
| **return\_status** | *out* | *y* |  |


### SetRecommLaneReq



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hudRecommLaneInfo** | *in* | *(ay)* |  |
| **return\_status** | *out* | *y* |  |


### SetTSRNavigationSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tsrNavigation** | *in* | *(ybby)* |  |
| **return\_status** | *out* | *y* |  |


### GetVINData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vinData** | *out* | *s* |  |



## Signals

### FuelTypeResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fuelType** | *in* | *y* |  |


### HUDResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hudStatus** | *in* | *y* |  |


### TSRResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tsrStatus** | *in* | *y* |  |


### GccConfigMgmtResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vin\_Character** | *in* | *(ay)* |  |


### TSRFeatureMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tsrMode** | *in* | *y* |  |

