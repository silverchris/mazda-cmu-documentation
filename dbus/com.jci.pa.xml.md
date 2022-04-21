
# Dbus interface API

**com.jci.pa**


## Methods

### StartPair



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pairMode** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### AbortPair



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **abortMode** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### PairToSelectedDevice



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **btaddress** | *in* | *(ay)* |  |
| **return\_value** | *out* | *i* |  |


### PairNumericCompResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **isPassecodeMatched** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### DeleteDevice



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **deviceId** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### DeleteAllDevices



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### RequestSearchDeviceList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetPairingPinCode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### SetPairingPinCode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pinCode** | *in* | *(ay)* |  |
| **return\_value** | *out* | *i* |  |


### GetPairingModuleSettings



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### RetrieveVehicleBtInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |



## Signals

### HftReadyStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hftReady** | *in* | *u* |  |
| **reasonCode** | *in* | *u* |  |


### PairingStatusResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **paPairingStatusResp** | *in* | *(ay)* |  |


### DeleteStatusResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **deleteStatus** | *in* | *u* |  |
| **deviceId** | *in* | *u* |  |


### SearchedDeviceListResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **numOfDevices** | *in* | *u* |  |
| **devIndex** | *in* | *u* |  |
| **deviceClass** | *in* | *u* |  |
| **btaddress** | *in* | *(ay)* |  |
| **btDeviceName** | *in* | *(ay)* |  |


### RequestedSearchListResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **totalSearchedDevices** | *in* | *u* |  |
| **searchedDeviceList** | *in* | *(ay)* |  |


### AuthenticationResp




### PairingPinCodeResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pinCode** | *in* | *(ay)* |  |


### PairingModuleResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **paSettings** | *in* | *(ay)* |  |


### VehicleBtInformationResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **paVehicleInfo** | *in* | *(ay)* |  |

