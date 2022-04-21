
# Dbus interface API

**com.jci.idm**


## Methods

### Get\_Config\_Data



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### ACK\_Config\_Data\_Recvd



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### StopScreenData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetNormalScreenData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetTrainingScreenData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetEndingScreenData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### EndingScreenSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ending\_scrn\_sett** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### MeterAmbDispSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **meter\_amb\_sett** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |



## Signals

### MeterAmbDisp\_Rq\_Rsp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **rq\_rsp\_status** | *in* | *u* |  |


### IDM\_EOLNormalScreen



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **eol\_normal** | *in* | *u* |  |


### EOLEndingScrn



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **eol\_endscrn** | *in* | *u* |  |


### Ending\_Scrn\_Setting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **endscrn\_sett** | *in* | *u* |  |


### MeterAmb\_Disp\_Setting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **amb\_sett** | *in* | *u* |  |


### Current\_Score



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **curr\_score** | *in* | *u* |  |


### Average\_Score



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **avg\_score** | *in* | *u* |  |


### Stage\_Number



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **stage\_num** | *in* | *u* |  |


### Driver\_Data



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **drv\_data** | ** | *(yayb)* |  |


### TransitionGraph\_Data



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **transGraph** | ** | *(aqy)* |  |


### CurrentBarData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **curr\_bar\_val** | *in* | *i* |  |


### CurrDrvTrend\_Brake



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **curr\_brk** | ** | *(yy)* |  |


### CurrDrvTrend\_Accel



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **curr\_accel** | ** | *(yy)* |  |


### CurrDrvTrend\_Steer



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **curr\_steer** | ** | *(yy)* |  |


### StageAchievedData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **stage\_data** | ** | *(yb)* |  |


### DrivingAdviceId



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **drv\_adviceId** | *in* | *u* |  |


### HVD\_IDMMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **idm\_mode** | *in* | *u* |  |


### HiScore\_Counter



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hi\_score\_val** | *in* | *u* |  |


### MeterAmbDisp\_SetRq\_Retry



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setrq\_retry** | *in* | *u* |  |


### End\_Of\_Screen\_Data



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **scrn\_type** | *in* | *u* |  |


### Display\_EndScreen



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **disp\_endscrn** | *in* | *u* |  |


### SpeedRest\_Flg



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **spd\_flg** | *in* | *u* |  |


### Ignition\_Sts



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ign\_sts** | *in* | *u* |  |

