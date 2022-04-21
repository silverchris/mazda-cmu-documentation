
# Dbus interface API

**com.jci.vbs.eem**


## Methods

### AvgFuelEco\_Rst\_CMU



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fuelEco\_Rst\_CMU** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### CstmzRq\_Trip\_Rst\_Mde



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **rq\_trip\_rst** | *in* | *y* |  |
| **return\_value** | *out* | *i* |  |


### BLM\_Startup\_Initiated



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **eem\_blm\_init** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |



## Signals

### CmltAvlFuelE\_D\_HEC



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cmltAvlFuelE** | *in* | *q* |  |


### AvgFuelEco\_Rst\_HEC



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fuelEco\_Rst** | *in* | *b* |  |


### PTiStpRdy\_B\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pTiStpRdy** | *in* | *b* |  |


### iStpDenyDPF\_B\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **denyDPF** | *in* | *b* |  |


### iStpDenyBatt\_B\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iStpDenyBatt** | *in* | *b* |  |


### iStpDenyAC\_B\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iStpDenyAC** | *in* | *b* |  |


### SISS\_EngineState



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sISS\_EngSt** | *in* | *y* |  |


### SISS\_WarningLamp\_G



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sISS\_WarnLmpG** | *in* | *y* |  |


### SISS\_WarningLamp\_R



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sISS\_WarnLmpR** | *in* | *y* |  |


### iStpDenyPwStr\_B\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **denyPwStr** | *in* | *b* |  |


### iStpDenyBrk\_B\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **denyBrk** | *in* | *b* |  |


### iStpDenyNrange\_B\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **denyNrange** | *in* | *b* |  |


### iStpKeySta\_B\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **keySta\_B** | *in* | *b* |  |


### CpctCrg\_Lvl\_D\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cpctCrg\_Lvl** | *in* | *y* |  |


### RgnPwr\_Lvl\_D\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **rgnPwr\_Lvl** | *in* | *y* |  |


### CapToElc\_B\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cap\_Elc** | *in* | *b* |  |


### SISSStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **s\_Status** | *in* | *b* |  |


### DistncUnitCnfg\_D\_Init



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **distnc\_Init** | *in* | *y* |  |


### DistncUnitCnfg\_Inh\_B\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **distnc\_Actl** | *in* | *b* |  |


### iStpReady\_Rq



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iStpRdy\_Rq** | *in* | *b* |  |


### FuelType\_Delivery



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fuel\_Type** | *in* | *y* |  |


### REGEN\_Types



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **gccConfigMgmtValue** | *in* | *y* |  |


### EndDis\_Eco\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **gccConfigMgmtValue** | *in* | *b* |  |


### CstmzRsp\_Trip\_Rst\_Mde



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **rsp\_trip\_rst** | *in* | *y* |  |


### CstmzStat\_Trip\_Rst\_Mde



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **stat\_trip\_rst** | *in* | *y* |  |


### Ignition\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ign\_sts** | *in* | *q* |  |


### StDis\_Eco\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **stDis\_Eco** | *in* | *u* |  |


### CMU\_Types



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cmu\_types** | *in* | *y* |  |


### CAN\_Missing



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **can\_missing\_ind** | *in* | *q* |  |


### Reset\_at\_ACC\_Off



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **reset\_cmu\_off** | *in* | *y* |  |


### EngAout\_N\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **engAout\_N** | *in* | *q* |  |


### HV\_CntRecord2



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hev\_HV\_CntRcrd2** | *in* | *(yyyy)* |  |


### DR\_SOC\_MON



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dr\_soc** | *in* | *y* |  |


### HVSYS2\_copy



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hvsys2\_copy\_resp** | *in* | *y* |  |


### HvEngPcm\_Tq\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hvEngPcm\_Tq** | *in* | *n* |  |


### HvTmPcm\_Tq\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hvTmPcm\_Tq** | *in* | *n* |  |


### HvRgBrk\_Tq\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hvRgBrk\_Tq** | *in* | *n* |  |


### HvMtrGen2Aout\_N\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hvMtrGen2Aout** | *in* | *n* |  |


### RvrseLmpReq\_D\_Actl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **rvrseLmpReq** | *in* | *y* |  |


### Sent\_Missed\_Signal\_Flag




### VehSpeedFlag



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vehspdflag** | *in* | *y* |  |


### OneMinuteTimerExpiry



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **oneMinTmrExpiry** | *in* | *b* |  |


### AvgFuelUnitCnfg\_D\_Init



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **avgfuelunit** | *in* | *y* |  |

