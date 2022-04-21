
# Dbus interface API

**com.jci.vbs.navi.tmc**


## Methods

### NaviCompassVal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **compass** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### NaviSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **navi** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### SetHUD\_Display\_Msg2



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **guidancePointData** | *in* | *(sy)* |  |
| **return\_status** | *out* | *y* |  |



## Signals

### ServiceListResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **providerList** | *in* | *(yayayayayay)* |  |


### ResponseToTMCSelection



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **rdstmcOperation** | *in* | *y* |  |
| **tmcSearchMode** | *in* | *y* |  |
| **countryCode** | *in* | *y* |  |
| **locationTableNumber** | *in* | *y* |  |
| **serviceIdentifier** | *in* | *y* |  |
| **quality** | *in* | *y* |  |
| **receptionStatus** | *in* | *y* |  |

