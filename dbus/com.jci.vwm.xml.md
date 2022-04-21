
# Dbus interface API

**com.jci.vwm**


## Methods

### getWGuideSettings



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### getActiveAlertList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **warningScreen** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### Maintenance\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **maintenanceScreen** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### Sched\_Maintenance\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **schedMaintenanceScreen** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### Tire\_Maintenance\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tireMaintenanceScreen** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### Oil\_Deterioration\_Maintenance\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **oilDeteriorationMaintenanceScreen** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### GetScdMntSettingData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### SetSchdMaintUpdateEnable



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vWM\_SchMaintUpdateModule** | *in* | *i* |  |
| **status** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### setOilChangeSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vWM\_OilChangeSettingStatus** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### setSchedMaintSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vWM\_ScdMaintSettingStatus** | *in* | *i* |  |


### setTireRotMaintSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vWM\_TireRotMaintSettingStatus** | *in* | *i* |  |


### SchMntResetRq



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **resetProperty** | *in* | *i* |  |


### setSchedMaintSetDist



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **schMaintDistRem** | *in* | *i* |  |


### setSchedMaintSetTime



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **schMaintTimeRem** | *in* | *i* |  |


### setTireRotMaintSetDist



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tireRotMaintDistRem** | *in* | *i* |  |


### setOilMaintSetDist



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **oiltMaintDistRem** | *in* | *i* |  |


### GetVWMData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |



## Signals

### wGuideSettings



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **maxHighPriorityAlerts** | *in* | *i* |  |


### wGuideActiveAlerts



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **warning\_info** | *in* | *(iay)* |  |


### wGuideNewHighAlerts



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **warning\_ha\_info** | *in* | *(iay)* |  |


### ScdMntSettingDataAsyncResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vWM\_Scheduled\_Maintenance\_Data** | *in* | *(buiiinnnnnnnuuuu)* |  |


### SchedMaintRemainingDist



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **scheduled\_maint\_dist** | *in* | *i* |  |
| **scheduled\_maint\_dist\_unit** | *in* | *u* |  |


### SchedMaintRemainingTime



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **scheduled\_maint\_time** | *in* | *i* |  |


### TireRotationRemainingDist



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tire\_rota\_rem\_dist** | *in* | *i* |  |
| **tire\_rota\_rem\_unit** | *in* | *u* |  |


### OilLife



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **oil\_life\_level** | *in* | *i* |  |
| **oil\_life\_DistRemaining** | *in* | *i* |  |


### VehicleStatusMonitor



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vehicle\_Status\_Monitor** | *in* | *b* |  |


### OilLevelStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vWM\_OilLevelStatus** | *in* | *i* |  |


### schdMntDue



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vWM\_ScheduleMaintUpdateEnable** | *in* | *i* |  |
| **status** | *in* | *b* |  |
| **vWM\_ScheduleMaint\_DueValue** | *in* | *i* |  |


### OilChangeRemainingDist



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **oilChangeDistRemaining** | *in* | *i* |  |
| **unit** | *in* | *u* |  |


### SchMntSettingChangeStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vWM\_SchMaintStatusChange** | *in* | *i* |  |


### Dismiss\_High\_Alert



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vWM\_High\_Alert\_Dismiss** | *in* | *i* |  |


### Curr\_VWMData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vWM\_Data** | *in* | *(iiiiubbbby)* |  |


### FSC\_Types



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fSC\_Type** | ** | *i* |  |


### VehicleModelType



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **model\_type** | *in* | *q* |  |
| **cMUModel** | *in* | *y* |  |

