
# Dbus interface API

**com.jci.dvd**


## Methods

### SwitchState



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **state** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### ChangeSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setting** | *in* | *u* |  |
| **value** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### GetSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setting** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### PinOperation



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cmd** | *in* | *u* |  |
| **pin** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### DeviceCommand



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cmd** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### ScrubberBarControl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **percentage** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### GetDvdStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dvdStatusData** | *out* | *(uuuuuuuiiuy)* |  |



## Signals

### DeviceStatusEvent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **event** | ** | *u* |  |


### PlayingStatusEvent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playingStatusData** | ** | *(qyyyyyyy)* |  |

