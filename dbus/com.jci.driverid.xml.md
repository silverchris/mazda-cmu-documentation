
# Dbus interface API

**com.jci.driverid**


## Methods

### Get\_DriveridConfig



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Set\_DriveridSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setting\_type** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### GetDriverIdData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_DriverList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Change\_DriverId



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **drv\_id** | *in* | *y* |  |
| **return\_value** | *out* | *i* |  |


### Change\_DriverNickname



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **nickname** | *in* | *(ay)* |  |
| **return\_value** | *out* | *i* |  |


### SynUp\_Ack\_Rcvd



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ack\_value** | *out* | *i* |  |



## Signals

### EOLConfig



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **eol\_config** | *in* | *q* |  |


### Setting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **driverid\_sett** | *in* | *b* |  |


### Curr\_DriverData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **curr\_drv** | ** | *(yayby)* |  |


### Curr\_DriverDataAsync



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **curr\_drv** | ** | *(yayby)* |  |


### Driver\_List



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **drv\_list** | *in* | *(a(yayby))* |  |


### Duplicate\_Nickname



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dup\_nickname** | *in* | *i* |  |


### SpeedRest\_Flg



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **spd\_flg** | *in* | *u* |  |


### ACC\_OFF



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **acc\_state** | ** | *b* |  |

