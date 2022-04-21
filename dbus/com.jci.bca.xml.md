
# Dbus interface API

**com.jci.bca**


## Methods

### ConnectRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **serviceId** | *in* | *u* |  |
| **btDeviceId** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### ConnectRequestHfpAndAvp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **btDeviceId** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### DisconnectRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **serviceId** | *in* | *u* |  |
| **btDeviceId** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### DisconnectRequestHfpAndAvp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **btHfpDeviceId** | *in* | *u* |  |
| **btAvpDeviceId** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### CancelConnect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cancelConnect** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### GetConnectStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **serviceId** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### QueryConnectStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **serviceId** | *in* | *u* |  |
| **connectionStatus** | *out* | *(iiii(ay))* |  |


### UnbarDevice



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **btDeviceId** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### BluetoothOn



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **isInfoToBeUpdatedToFlash** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### BluetoothOff



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **isInfoToBeUpdatedToFlash** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### StartAdd



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **addServiceId** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### ConnectAll



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **btDeviceId** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### DisconnectAll



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetServiceId



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **serviceType** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### ReadBluetoothSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### AvailablePairedDeviceList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetFeatureStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **isbcaReady** | *out* | *i* |  |
| **reasonCode** | *out* | *i* |  |


### SupportedProfiles



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **btDeviceId** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### SetDontShowOnConnectionSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **btDeviceId** | *in* | *u* |  |
| **setting** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### GetDontShowOnConnectionSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **btDeviceId** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### AAutoEnableBtResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **select** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### AAutoNoEntryAvailableResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **select** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### PairingStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *in* | *u* |  |
| **error** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### DeviceDeleteStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **deleteStatus** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### CallStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **bthfstate** | *in* | *u* |  |
| **call1status** | *in* | *u* |  |
| **call2status** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### SetCommSettingsResetStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### SetMP911EmergencyCallStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |



## Signals

### DontShowOnConnectionSettingStatusResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **btDeviceId** | *in* | *u* |  |
| **setting** | *in* | *b* |  |


### ConnectionStatusResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **serviceId** | *in* | *u* |  |
| **connStatus** | *in* | *u* |  |
| **btDeviceId** | *in* | *u* |  |
| **status** | *in* | *u* |  |
| **terminalPath** | *in* | *(ay)* |  |


### HftReadyStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hftReady** | *in* | *u* |  |
| **reasonCode** | *in* | *u* |  |
| **appId** | *in* | *u* |  |


### ReadyStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **isReady** | *in* | *u* |  |
| **reasonCode** | *in* | *u* |  |


### AddStatusResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **addServiceId** | *in* | *u* |  |
| **status** | *in* | *u* |  |


### DeviceUnbarringStatusResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **btDeviceId** | *in* | *u* |  |
| **status** | *in* | *u* |  |


### DeviceBluetoothSettingResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **btSetting** | *in* | *b* |  |


### AvailablePairedListResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **totalPairedDevices** | *in* | *u* |  |
| **pairedDeviceList** | *in* | *(ay)* |  |


### SupportedProfilesResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **supportedProfiles** | *in* | *(ay)* |  |


### FirstHfpSupportedInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **isHfpSupportedDevicePresent** | *in* | *b* |  |


### CarPlayConnectionStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connStatus** | *in* | *u* |  |
| **carPlayDeviceId** | *in* | *u* |  |


### AAutoEnableBt




### AAutoNoEntryAvailable



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **deleteDeviceId** | *in* | *u* |  |


### ReqStartAndroidAutoPairing




### ReqStopAndroidAutoPairing




### ReqDeleteDevice



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **deleteDeviceId** | *in* | *u* |  |


### AAPairingSeqResult



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **result** | *in* | *b* |  |


### AndroidAutoPairingTimeout




### RequestStartAutoDownload



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **btDeviceId** | *in* | *u* |  |


### DisableBluetoothRsp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **activeCallStatus** | *in* | *u* |  |


### ConnectingCarPlayError



