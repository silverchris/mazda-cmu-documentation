
# Dbus interface API

**com.jci.btrvr**


## Methods

### StartRemoteVr



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### StopRemoteVr



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### EnableEyesFreemode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### DisableEyesFreeMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetRemoteVrStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### SetDontShowSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dontShowSettingValue** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### GetDontShowSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |



## Signals

### RemoteVrStatusResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *in* | *u* |  |


### DontShowSettingResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dontShowSettingValue** | *in* | *u* |  |


### ShowWinkSettingResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **showWinkSettingValue** | *in* | *u* |  |

