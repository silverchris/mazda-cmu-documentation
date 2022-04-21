
# Dbus interface API

**com.jci.xm**


## Methods

### GetModeStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### ModeChange



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **xm\_mode** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### FavoriteModeChange



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **xm\_mode** | *in* | *i* |  |
| **tune\_value\_sid** | *in* | *y* |  |
| **tune\_value\_ch** | *in* | *y* |  |
| **return\_value** | *out* | *i* |  |


### TuneRelative



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tune\_direction** | *in* | *i* |  |
| **tune\_steps** | *in* | *y* |  |
| **return\_value** | *out* | *i* |  |


### TuneAbsolute



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tune\_value\_sid** | *in* | *y* |  |
| **tune\_value\_ch** | *in* | *y* |  |
| **return\_value** | *out* | *i* |  |


### MuteReq



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **mute\_direction** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### IsParentalLockEnabled



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **parental\_lock\_status** | *out* | *i* |  |


### IsParentalLockPINSet



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **parental\_pin\_status** | *out* | *i* |  |


### IsChannelLocked



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **channel\_id** | *in* | *y* |  |
| **channel\_lock\_status** | *out* | *i* |  |


### GetParentalLockPIN



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetDefaultParentalLockPIN



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### SetParentalLockPIN



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **parental\_lock\_pin** | *in* | *(yyyy)* |  |
| **return\_value** | *out* | *i* |  |


### SetParentalLockStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **parental\_lock\_status** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### SetChannelLock



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **channel\_lock\_status** | *in* | *i* |  |
| **channel\_id** | *in* | *y* |  |
| **return\_value** | *out* | *i* |  |


### DisplayXMSettings



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### ScanReq



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **scan\_req\_type** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### GetConfigStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Fav\_Seek\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fav\_seek\_dir** | *in* | *i* |  |
| **current\_ch** | *in* | *y* |  |
| **return\_value** | *out* | *i* |  |


### GetInstallStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |



## Signals

### TunerStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tuner\_status** | ** | *(yyyyybayi)* |  |


### MuteStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **mute\_direction** | ** | *i* |  |


### ChannelListUpdated



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **channel\_list\_status** | *in* | *y* |  |


### AntennaStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **antenna\_status** | *in* | *(yy)* |  |


### ParentalLockPin



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **parental\_pin** | *in* | *(yyyy)* |  |


### DefaultParentalLockPin



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **default\_parental\_pin** | *in* | *(yyyy)* |  |


### MetadataAvailable



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **metadataType** | *in* | *i* |  |


### MetadataChange



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **metadataStatus** | *in* | *(bbbb)* |  |


### ModeStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **modeStatus** | *in* | *i* |  |


### ConfigStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **config\_status** | *in* | *i* |  |


### InstallStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **install\_status** | *in* | *i* |  |

