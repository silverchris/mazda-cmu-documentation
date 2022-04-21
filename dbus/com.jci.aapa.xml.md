
# Dbus interface API

**com.jci.aapa**


## Methods

### MDSettingModeData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **selectMode** | *in* | *u* |  |


### VideoProjectionEventToMD



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **videoProjectionEvent** | *in* | *u* |  |


### InputKey



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **keyCode** | *in* | *u* |  |
| **absolute** | *in* | *b* |  |
| **step** | *in* | *i* |  |


### SetRouteState



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **state** | *in* | *u* |  |


### GetNowPlayingInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **nowPlayingInfo** | *out* | *(yssss)* |  |
| **return\_value** | *out* | *i* |  |


### BTPairingResult



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **result** | *in* | *b* |  |


### BTReadyToPair



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **alreadyPaired** | *in* | *b* |  |


### SendBTAuthenticationData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **btdata** | *in* | *s* |  |
| **len** | *in* | *u* |  |


### SetVehicleBtMacAddress



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **macaddr** | *in* | *s* |  |
| **maclen** | *in* | *u* |  |


### NotifyBTHFCallStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *in* | *b* |  |
| **macaddr** | *in* | *s* |  |


### IntentPhoneCall



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **phonenumber** | *in* | *s* |  |


### DialogWinkStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *in* | *b* |  |


### ClearLastFocus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **focusInfo** | *in* | *(bb)* |  |


### SbnStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *in* | *b* |  |


### GetAOASessionStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *out* | *b* |  |
| **macaddr** | *out* | *s* |  |
| **maclen** | *out* | *u* |  |


### GetAvailable



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **available** | *out* | *y* |  |


### SetNativeTurnByTurnStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setNativeTurnByTurnStatus** | *in* | *(b)* |  |
| **setNativeTurnByTurnStatus\_reply** | *out* | *(i)* |  |


### SetMP911EmergencyCallStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |



## Signals

### AOASessionStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **enable** | *in* | *b* |  |


### SendSessionInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **deviceName** | *in* | *s* |  |


### VideoProjectionRequestFromMD



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **enable** | *in* | *u* |  |


### NowPlayingInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **nowPlayingInfo** | *in* | *(yssss)* |  |


### MDModeDisplayFirstDialog



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **displayFirstDialog** | *in* | *b* |  |


### DisplayReconnectingDialog



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **enable** | *in* | *b* |  |


### StartBtConnection




### BTPairingRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **macaddr** | *in* | *s* |  |
| **maclen** | *in* | *u* |  |
| **method** | *in* | *b* |  |


### GetVehicleBtMacAddress




### NotifySpeedThreshold



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **enable** | *in* | *b* |  |


### DisplaySbnInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **info** | *in* | *u* |  |


### NotifyAudioFocusStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *in* | *u* |  |


### NotifyBTConnectionComplete



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **enable** | *in* | *b* |  |


### Available



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **available** | *in* | *y* |  |


### NotifyStopAndSetup



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **displaySASDialog** | *in* | *u* |  |


### NotifyNoVideoSinkSetup



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **displayNVSSDialog** | *in* | *b* |  |


### NotifyDeviceNotResponding



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **displayDNR** | *in* | *b* |  |


### NotifyASRStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **enable** | *in* | *b* |  |


### ProjectionStatusResult



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **enable** | *in* | *b* |  |


### DisplayStopForSetupDialog



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **enable** | *in* | *b* |  |


### NotifyAANaviStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *in* | *i* |  |


### GetNativeTurnByTurnStatusRequest




### NotifyDeviceConnection



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *in* | *b* |  |

