
# Dbus interface API

**com.jci.vbs.drvididm**


## Methods

### BLM\_Startup\_Initiated



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **drvididm\_blm\_init** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### IDM\_AmbientDisplay\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cstmzRq\_Ind\_Clr\_OnOff** | *in* | *y* |  |
| **return\_value** | *out* | *i* |  |


### BLM\_Startup\_Initiated\_Driver



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **drvididm\_blm\_init\_driver** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### DI\_Reliable\_Delivery



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **reliable\_dr\_id** | *in* | *y* |  |
| **return\_value** | *out* | *i* |  |


### CurrentScore\_Hec



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **current\_score\_hec** | *in* | *y* |  |
| **return\_value** | *out* | *i* |  |



## Signals

### Ignition\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ign\_sts** | *in* | *q* |  |


### Eng\_StartKey



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **eng\_start\_key** | *in* | *q* |  |


### EngineState



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **engine\_state** | *in* | *q* |  |


### IDM\_SD\_Evl\_D\_Num



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **idm\_SD\_EvlDNum** | *in* | *q* |  |


### CAN\_Missing\_Error



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **can\_miss\_Err** | *in* | *n* |  |


### Sds\_TotNG\_Par\_D\_Rq\_2



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sds\_TotNGPar\_Req2** | *in* | *q* |  |


### CstmzStat\_Ind\_Clr\_OnOff



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cstmzStat\_Clr\_Req** | *in* | *y* |  |


### IDM\_SD\_CalcInfo\_Category



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **idm\_calculateInfo\_category** | *in* | *n* |  |


### IDM\_SD\_CalcInfo\_Value



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **idm\_calculateInfo\_value** | *in* | *n* |  |


### Sds\_TotSD\_Avl\_D\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sds\_TotSD\_AvlDActl** | *in* | *y* |  |


### Sds\_SD\_Stage\_D\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sds\_SD\_StageDActl** | *in* | *y* |  |


### Sds\_TotSD\_Point\_D\_Actl\_2



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sds\_TotSD\_PointDActl2** | *in* | *n* |  |


### EndDis\_IDM\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **endDis\_IDMReq** | *in* | *y* |  |


### StDis\_IDM\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **stDis\_IDMReq** | *in* | *y* |  |


### CstmzRsp\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cstmzRspStatus** | *in* | *y* |  |


### Sds\_SD\_Stage\_D\_Actl2



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sds\_SD\_StageDActl2** | *in* | *y* |  |


### Stat\_Ign\_5s



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **stat\_Ign5s** | *in* | *b* |  |


### driverIdentification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **driverId** | *in* | *y* |  |


### Data\_Ack\_DriverNumber



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **data\_ackdrivernumber** | *in* | *b* |  |


### All\_sinal\_Idm



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **allsinal\_idm** | *in* | *b* |  |


### All\_sinal\_Drv



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **allsinal\_drv** | *in* | *b* |  |


### Timer\_Expired\_1min




### CstmzRsp\_49bStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cstmzRspStatus\_49b** | *in* | *y* |  |

