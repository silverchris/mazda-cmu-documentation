
# Dbus interface API

**com.jci.itts**


## Methods

### RequestMemoryInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **devIdList** | *in* | *(au)* |  |
| **memoryInfo** | *out* | *(a(uui)u)* |  |
| **return\_value** | *out* | *i* |  |


### StoreTag



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tagMaxCntFlash** | *in* | *u* |  |
| **devIdList** | *in* | *(au)* |  |
| **tagStoreStatus** | *out* | *i* |  |
| **memoryInfo** | *out* | *(a(uui)u)* |  |


### TransferTag



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tagMaxCntiPod** | *in* | *u* |  |
| **devIdList** | *in* | *(au)* |  |
| **tagTransferStatus** | *out* | *i* |  |
| **memoryInfo** | *out* | *(a(uuu)uu)* |  |


### RadioConnectionStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connectStandbyStat** | *in* | *y* |  |
| **return\_value** | *out* | *i* |  |


### RadioModeChange



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **modeChangeSrc** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### RadioOnOff



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **radioOnOffStatus** | *in* | *y* |  |
| **return\_value** | *out* | *i* |  |


### RadioStationChange



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **frequency** | *in* | *q* |  |
| **return\_value** | *out* | *i* |  |


### RadioTrackChange



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **trackChange** | *in* | *y* |  |
| **return\_value** | *out* | *i* |  |


### UpdateMetadata



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tagInfo** | *in* | *(ay)* |  |
| **return\_value** | *out* | *i* |  |


### ClearNVM



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tagsToClearCnt** | *in* | *u* |  |
| **tagsClearedCnt** | *out* | *u* |  |
| **return\_value** | *out* | *i* |  |


### CheckConnDev



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |



## Signals

### AppleDevConnected



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **devConn** | *in* | *(usiu)* |  |
| **tagsNVM** | *in* | *b* |  |


### AppleDevDisconnected



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **devId** | *in* | *i* |  |


### TaggingAvailable



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **enableTagging** | *in* | *i* |  |


### TaggingErrorDevice



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tagTransferStatus** | *in* | *i* |  |

