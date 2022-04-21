
# Dbus interface API

**com.jci.bthf**


## Methods

### Dial



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dialNumber** | *in* | *(ay)* |  |
| **dialPrompt** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### EmergencyDial



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dialNumber** | *in* | *(ay)* |  |
| **return\_value** | *out* | *i* |  |


### Redial



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### HangupCall



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### RejectCall



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### AcceptCall



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### MuteCall



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### UnmuteCall



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### SwapCall



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### HeldCall



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### UnHeldCall



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### JoinCall



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### TransferCall



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **transferType** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### SendDtmf



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dtmfDigits** | *in* | *(ay)* |  |
| **return\_value** | *out* | *i* |  |


### StartPhoneVr



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### StopPhoneVr



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### StartBargein



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### StopBargein



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### CallSettings



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **isIncallAutoXferEnabled** | *in* | *u* |  |
| **isOutCallAutoXferEnabled** | *in* | *u* |  |
| **isActiveCallAutoXferEnabled** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### RingToneSettings



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ringToneTypeSupported** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### AutoAnswerSettings



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **autoAnswerValue** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### RampupRingToneSettings



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **isRampUpRingToneSupported** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### DoNotDisturbSettings



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **isDoNotDisturbEnabled** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### QueryCallStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### EmergencyCallStart



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### EmergencyCallStop



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetBthfSettingData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### ResetBthfCommunicationSettings



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |



## Signals

### CallStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **bthfstate** | *in* | *u* |  |
| **call1status** | *in* | *u* |  |
| **call2status** | *in* | *u* |  |
| **call1Number** | *in* | *(ay)* |  |
| **call2Number** | *in* | *(ay)* |  |


### BatteryIndicator



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **minValue** | *in* | *u* |  |
| **maxValue** | *in* | *u* |  |
| **currentValue** | *in* | *u* |  |


### SignalStrength



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **minValue** | *in* | *u* |  |
| **maxValue** | *in* | *u* |  |
| **currentValue** | *in* | *u* |  |


### RoamIndicator



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **value** | *in* | *u* |  |


### NewServiceIndicator



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **value** | *in* | *b* |  |


### PhoneChargeIndicator



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **value** | *in* | *u* |  |


### SmsPresentIndicator



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **value** | *in* | *b* |  |


### VoiceMailIndicator



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **value** | *in* | *b* |  |


### LowBatteryIndicator



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **value** | *in* | *b* |  |


### BthfReadyStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hftReady** | *in* | *u* |  |
| **reasonCode** | *in* | *u* |  |


### BthfBusyReason



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **busyReason** | *in* | *u* |  |


### MicStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **isMicMuted** | *in* | *b* |  |


### BargeinStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **isBargeinActive** | *in* | *b* |  |


### BthfSettingsResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **callsettings** | *in* | *(ay)* |  |


### FailureReasonCodes



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **errorType** | *in* | *u* |  |

