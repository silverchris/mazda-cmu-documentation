
# Dbus interface API

**com.jci.eem**


## Methods

### GetEquippedData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### SetEEMUpdateScreenEnable



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **screen\_type** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### CMUResetSettingRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **reset\_active** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### CMU\_UMPResetRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *u* |  |


### EndingScreenSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **endSetActive** | *in* | *u* |  |



## Signals

### SetEquippedData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **feature\_attached** | ** | *u* |  |


### Setting\_ResetResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setting\_resetResponse** | ** | *(uu)* |  |


### CMU\_UMPResetResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cMU\_UMPresetResponse** | ** | *(u)* |  |


### HVD\_EEMEndSet



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **eEMEndSet\_Active** | ** | *u* |  |


### StDisEco\_Active



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **stDisEco\_Active** | ** | *u* |  |


### HVD\_CstmzRq\_Trip



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cstmzRq\_Trip** | ** | *u* |  |


### EEMEndDispConf



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **eEMEndDisp\_Enabled** | ** | *u* |  |


### IEloop\_ControlStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iEloop\_Control\_sts** | ** | *(uuu)* |  |


### Cumulative\_Avg\_Fuel\_Economy



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **value** | ** | *((u)u)* |  |


### iStop\_mode\_ControlStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iStop\_mode** | ** | *u* |  |


### iStop\_status\_ControlStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **istop\_status** | ** | *((y)(y)(y)(y))* |  |


### iStop\_time\_ControlStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iStop\_time** | ** | *(uu)* |  |


### iStop\_error\_ControlStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iStop\_error** | ** | *(bbu)* |  |


### iStop\_Effective\_Rate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iStop\_Eff\_Rate** | ** | *(y)* |  |


### iStop\_Effective\_time



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iStop\_effectiveness\_time** | ** | *((uu)(u))* |  |


### iEloop\_Effective\_Rate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iEloop\_Eff\_Rate** | ** | *(y)* |  |


### iEloop\_Effective\_Data



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iEloop\_Effective\_data** | ** | *((q)u(q)u)* |  |


### CO2\_reduction



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cO2\_reduction** | ** | *(qy)* |  |


### CO2\_Reduction\_prevIGNcycle



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cO2\_reduction\_prevIGcycl** | ** | *(qy)* |  |


### EEM\_Total\_Saved\_Distance



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **total\_Saved\_Distance** | ** | *(uy)* |  |


### Curr\_drive\_fuel\_eco\_line\_graph\_data



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fuel\_eco\_dataY\_line** | ** | *(ya(q)u)* |  |


### Curr\_drive\_fuel\_eco\_bar\_graph\_data



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fuel\_eco\_dataY\_bar** | ** | *(ya(q)u)* |  |


### Curr\_drive\_fuel\_eco\_SixtyMin\_bar\_graph\_data



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fuel\_eco\_dataY\_sixtyMinbar** | ** | *(ya(q)u)* |  |


### Curr\_drive\_fuel\_eco\_OneMin\_bar\_graph\_data



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fuel\_eco\_dataY\_oneMinbar** | ** | *(ya(q)u)* |  |


### Curr\_drive\_fuel\_eco\_HEV\_SixtyMin\_bar\_graph\_data



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fuel\_eco\_dataY\_sixtyMinbar** | ** | *(ya(qybb)u)* |  |


### Curr\_drive\_fuel\_eco\_HEV\_OneMin\_bar\_graph\_data



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fuel\_eco\_dataY\_oneMinbar** | ** | *(ya(qybb)u)* |  |


### OneDriveEVDistance



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **driveEV\_dist** | ** | *(qyy)* |  |


### HEVSendEnergyFlowSignals



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **energyFlowSignals** | ** | *(yyyyyu)* |  |


### HEVSendBatteryDisplayLvl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **battLvl** | ** | *u* |  |


### DistDriveEV



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **driveEV\_dist** | ** | *(uyy)* |  |


### Cumm\_fuel\_eco\_reset\_graph\_data



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fuel\_eco\_dataY\_reset** | ** | *(ya(u)u)* |  |


### new\_Curr\_drive\_fuel\_eco\_per\_inst\_bar\_graph\_data



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **new\_valueY** | ** | *((q)bu)* |  |


### new\_Curr\_drive\_fuel\_eco\_line\_graph\_data



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **new\_valueY** | ** | *((q)bu)* |  |


### Curr\_avg\_drive\_fuel\_eco



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **curr\_fuel\_eco** | ** | *((q)bu)* |  |


### Cum\_fuel\_eco\_after\_reset\_data\_Y1



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **curr\_fuel\_eco** | ** | *((u)u)* |  |


### UMP\_Reset\_enable



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **button\_enable** | ** | *u* |  |


### End\_Of\_Screen\_Data




### Screen\_Ending\_message



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ending\_screen\_message** | ** | *(b)* |  |


### Ignition\_Sts



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ign\_sts** | *in* | *u* |  |


### HVD\_LAST\_DISPLAYED\_SCREEN



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **previous\_Screen** | ** | *u* |  |


### ControlStatusSendTireStatusSignals



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tireStatusSignals** | ** | *(yu)* |  |

