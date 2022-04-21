
# Dbus interface API

**com.jci.bteca**


## Methods

### AbortCall



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### TransferToHandset



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### TransferFromHandset



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### BargeIntoCall



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetBTECAEnabledValue



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### SetBTECAEnabledValue



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **isBTECAenabled** | *in* | *y* |  |
| **return\_value** | *out* | *i* |  |


### IsBTECASupported



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### RetryEcall



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### ResetEnableSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |



## Signals

### EnabledChange



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **isBTECAenabled** | ** | *y* |  |


### CollisionDetected



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **phoneConnected** | ** | *b* |  |


### PhoneFoundStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **found** | ** | *b* |  |


### CollisionDetectedTimerStart




### CollisionDetectedTimerExpired




### CallSuccess




### CallNotSuccess



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **maxAttempts** | ** | *b* |  |


### AudioTransferredToPhone




### AudioTransferredToCar




### EndCall




### EmergencyCallFailure




### MP911EmergencyCallStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **emergencyStatus** | ** | *i* |  |


### PhoneBTConnectionLost




### TransferredToHandset



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **transferStaus** | ** | *b* |  |


### TransferredFromHandset



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **transferStaus** | ** | *b* |  |
| **stillConnecting** | ** | *b* |  |


### ConnectedTimerStart




### ShowPSAPInfoInscription



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **showInscription** | ** | *b* |  |


### SetTransferredValid



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **transferredValid** | ** | *b* |  |


### NotifyCarPlaySession



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **carPlaySession** | ** | *b* |  |

