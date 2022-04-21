
# Dbus interface API

**com.jci.carplay**


## Methods

### PressKey



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pressKey** | *in* | *(ub)* |  |
| **pressKey\_reply** | *out* | *(u)* |  |


### RotateKnob



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **rotateKnob** | *in* | *(u)* |  |
| **rotateKnob\_reply** | *out* | *(u)* |  |


### PanKnob



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **panKnob** | *in* | *(u)* |  |
| **panKnob\_reply** | *out* | *(u)* |  |


### SiriLaunch



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **siriLaunch** | *in* | *(u)* |  |
| **siriLaunch\_reply** | *out* | *(u)* |  |


### TouchScreen



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **touchScreen** | *in* | *(qqb)* |  |
| **touchScreen\_reply** | *out* | *(u)* |  |


### DisableTouchScreenCoordinate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **disableTouchScreenCoordinate** | *in* | *(uuuu)* |  |
| **disableTouchScreenCoordinate\_reply** | *out* | *(u)* |  |


### SelectDevice



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **selectDevice** | *in* | *(u)* |  |
| **selectDevice\_reply** | *out* | *(u)* |  |


### ScreenResourceAvailable



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **screenResourceAvailable** | *in* | *(uu)* |  |
| **screenResourceAvailable\_reply** | *out* | *(u)* |  |


### ScreenAcquireResource



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **screenAcquireResource** | *in* | *(u)* |  |
| **screenAcquireResource\_reply** | *out* | *(u)* |  |


### SetCurrentNativeScreen



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setCurrentNativeScreen** | *in* | *(u)* |  |
| **setCurrentNativeScreen\_reply** | *out* | *(u)* |  |


### SetTurnByTurnStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setTurnByTurnStatus** | *in* | *(b)* |  |
| **setTurnByTurnStatus\_reply** | *out* | *(u)* |  |


### SetPhoneCallStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setPhoneCallStatus** | *in* | *(b)* |  |
| **setPhoneCallStatus\_reply** | *out* | *(u)* |  |


### SetNotifyAudioStreamState



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setNotifyAudioStreamState** | *in* | *(b)* |  |
| **setNotifyAudioStreamState\_reply** | *out* | *(u)* |  |


### AcceptCallRequest




### GetNowPlayingInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **getNowPlayingInfo\_reply** | *out* | *((sssss)u)* |  |


### GetConnectDeviceInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **getConnectDeviceInfo\_reply** | *out* | *((s)(ssuusss)b)* |  |


### SetVehicleBtMacAddress



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vehicleBtMacAddress** | *in* | *s* |  |
| **vehicleBtMacAddressLength** | *in* | *u* |  |
| **vehicleBtMacAddressReply** | *out* | *u* |  |


### ClearLastFocus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **clearLastFocus** | *in* | *(bb)* |  |
| **clearLastFocus\_reply** | *out* | *(u)* |  |


### EnableCarPlayConnection



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **enableCarPlayConnection** | *in* | *(sub)* |  |
| **enableCarPlayConnection\_reply** | *out* | *(u)* |  |


### DisplayDialogResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **displayDialogResponse** | *in* | *(u)* |  |
| **displayDialogResponse\_reply** | *out* | *(u)* |  |


### UpdateBTAudioStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **updateBTAudioStatusInfo** | *in* | *(u)* |  |
| **updateBTAudioStatus\_reply** | *out* | *(u)* |  |


### MethodCallClientDial



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **methodCallClientDial** | *in* | *(suu)* |  |
| **methodCallClientDial\_reply** | *out* | *(u)* |  |


### MethodCancelClientDial



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **methodCancelClientDial** | *in* | *(u)* |  |
| **methodCancelClientDial\_reply** | *out* | *(u)* |  |


### SetMP911EmergencyCallStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |



## Signals

### DisableBluetoothSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **disableBluetoothInfo** | ** | *(s)* |  |


### SessionActiveSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionActiveInfo** | ** | *(tu)* |  |


### GetCurrentNativeScreenRequestSignal




### DeviceErrorSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **deviceErrorInfo** | ** | *(tu)* |  |


### SessionDeactiveSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionDeactiveInfo** | ** | *(t)* |  |


### NativeUILaunchSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **nativeUILaunchInfo** | ** | *(u)* |  |


### ScreenResourceRequestSignal




### ScreenResourceRequestTimeoutSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **timeoutInfo** | ** | *(u)* |  |


### NativeScreenDisplayRequestSignal




### GetTurnByTurnStatusRequestSignal




### TurnByTurnEntitySignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **entityInfo** | ** | *(u)* |  |


### GetPhoneCallStatusRequestSignal




### UpdateCallStatusInfoSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **callStatusInfo** | ** | *(ssuusss)* |  |


### SpeechEntitySignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **entityInfo** | ** | *(u)* |  |


### UpdateNowPlayingInfoSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **nowPlayingInfo** | ** | *((sssss))* |  |


### GetVehicleBtMacAddress




### FeatureAvailableSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **availableInfo** | ** | *(u)* |  |


### DisplayDialogSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dialogInfo** | ** | *(ussu)* |  |


### UpdateAudioStatusSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **audioStatus** | ** | *(u)* |  |


### DisconnectedDeviceSignal




### UsbPortStatusSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **usbPortStatusInfo** | ** | *(uu)* |  |


### ClientConnectedSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **clientConnectedInfo** | ** | *(tbb)* |  |


### ClientDisconnectedSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **clientDisconnectedInfo** | ** | *(t)* |  |


### ScreenResourceReadySignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **screenResourceReady** | ** | *(tb)* |  |


### DisplayDialogResponseSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **displayDialogResponseInfo** | ** | *(u)* |  |


### UsbErrorStatusSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **usbErrorStatusInfo** | ** | *(u)* |  |

