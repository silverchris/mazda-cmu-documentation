
# Dbus interface API

**com.jci.traffic**


## Methods

### SetNewMapUpdateEnable\_async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **enable** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### SetMapInFocus\_async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **focus** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### GetGpsInfo\_async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |



## Signals

### BGColorInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **colorR** | ** | *u* |  |
| **colorG** | ** | *u* |  |
| **colorB** | ** | *u* |  |


### NewTrafficMap



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **trafficMapId** | ** | *u* |  |


### MapUpdate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **mapType** | ** | *u* |  |
| **mapInfo** | ** | *(a(us))* |  |


### GpsInfoUpdate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **gpsInfo** | ** | *(iiu)* |  |


### LockedToStation



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **lockStatus** | ** | *u* |  |


### ApplicationStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **appStatus** | ** | *u* |  |


### LastTileUpdatedTime



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **lastUpdatedTime** | ** | *u* |  |


### TestModeText



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **testText** | ** | *s* |  |


### VICSFrequencyChangeAck



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **frequency** | ** | *d* |  |
| **state** | ** | *i* |  |

