
# Dbus interface API

**com.jci.lvds**


## Methods

### SetBrightness



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **brightnessLevel** | *in* | *(uuyy)* |  |
| **return\_value** | *out* | *n* |  |


### GetSoftwareTPVersion



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **softwareTPVersion** | *in* | *(uuyy)* |  |
| **return\_tpSoftwareVer** | *out* | *s* |  |


### GetSoftwareDispVersion



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **softwareDispVersion** | *in* | *(uuyy)* |  |
| **return\_dispSoftwareVer** | *out* | *s* |  |


### SetNormalMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **normalMode** | *in* | *(uuyy)* |  |
| **return\_NormalMode** | *out* | *s* |  |


### SetSleepMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sleepMode** | *in* | *(uuyy)* |  |
| **return\_SleepMode** | *out* | *s* |  |


### SetDiagMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **diagMode** | *in* | *(uuyy)* |  |
| **return\_DiagMode** | *out* | *s* |  |


### SetExtendMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **extendMode** | *in* | *(uuyy)* |  |
| **return\_ExtendMode** | *out* | *s* |  |


### SetACCOff



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **aCCOff** | *in* | *(uuyy)* |  |
| **return\_ACCOff** | *out* | *n* |  |


### SetDispOn



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dispOn** | *in* | *(uuyy)* |  |
| **return\_DispOn** | *out* | *n* |  |


### SetDispOff



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dispOff** | *in* | *(uuyy)* |  |
| **return\_DispOff** | *out* | *n* |  |


### EnablePRBS



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **enablePRBSAutoTest** | *in* | *(uuyy)* |  |
| **return\_EnPRBS** | *out* | *s* |  |


### DisablePRBS



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **disablePRBSAutoTest** | *in* | *(uuyy)* |  |
| **return\_DisPRBS** | *out* | *s* |  |


### PRBSReport



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pRBSAutoTestReport** | *in* | *(uuyy)* |  |
| **return\_PRBSReport** | *out* | *s* |  |


### SystemACCMonitoring



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *u* |  |
| **return\_status** | *out* | *u* |  |


### SpeedRestriction



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *u* |  |
| **return\_status** | *out* | *u* |  |


### SetHdcpMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **mode** | *in* | *u* |  |
| **return\_status** | *out* | *u* |  |


### GetErrorEncounteredStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_status** | *out* | *u* |  |


### BlmLvdsReady



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *u* |  |
| **return\_status** | *out* | *u* |  |


### FaultStatusResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **faultId** | *in* | *u* |  |
| **status** | *in* | *u* |  |
| **return\_status** | *out* | *u* |  |


### GetDisplayStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *u* |  |
| **return\_status** | *out* | *u* |  |


### GetHdcpState



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_status** | *out* | *u* |  |


### SetVideoTuning



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **videoTuning** | *in* | *(uuuu)* |  |
| **return\_videoTuning** | *out* | *u* |  |


### GetTunedValues



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *u* |  |
| **return\_status** | *out* | *u* |  |


### GetRegisterDump



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **regType** | *in* | *u* |  |
| **all** | *in* | *b* |  |
| **start** | *in* | *y* |  |
| **stop** | *in* | *y* |  |
| **return\_status** | *out* | *u* |  |


### TouchSimulation



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **touchEvents** | *in* | *(y(qq)(qq)(qq)(qq))* |  |
| **return\_status** | *out* | *u* |  |


### BrightnessRamp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **brightnessLevel** | *in* | *(uuyy)* |  |
| **return\_value** | *out* | *n* |  |


### SetSpreadSpectrum



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **spreadLevel** | *in* | *u* |  |
| **return\_status** | *out* | *u* |  |


### SetCMLLevel



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cMLLevel** | *in* | *u* |  |
| **return\_status** | *out* | *u* |  |



## Signals

### brightNessLevelResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **brightNessLvl** | ** | *n* |  |


### TPVersionResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tPVersion** | ** | *(us)* |  |


### displayVersion



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dispVersion** | ** | *(us)* |  |


### NormalModeResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **normalModeResp** | ** | *n* |  |


### SleepModeResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sleepModeResp** | ** | *n* |  |


### DiagModeResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **diagModeResp** | ** | *n* |  |


### ExtendModeResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **extendModeResp** | ** | *n* |  |


### EnablePRBSResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **enablePRBSResp** | ** | *n* |  |


### DisablePRBSResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **disablePRBSResp** | ** | *n* |  |


### PRBSReportResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pRBSReportResp** | ** | *n* |  |


### ACCOffResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **aCCOff** | ** | *n* |  |


### DispOnResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dispOn** | ** | *n* |  |


### DispOffResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dispOff** | ** | *n* |  |


### CurrentStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **curStat** | ** | *(uuyy)* |  |


### FaultStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fault** | ** | *(uuyy)* |  |


### ErrorStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **error** | ** | *n* |  |


### TouchIgnoreStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **touchIgnoreStatus** | ** | *u* |  |


### ErrorEncounteredAlert



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **errorAlert** | ** | *u* |  |


### DisplayStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **displayStatus** | ** | *(ay)* |  |


### HdcpState



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hdcpState** | ** | *u* |  |


### HdcpModeStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hdcpModeStatus** | ** | *u* |  |


### VideoTuning



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **videoTuning** | ** | *u* |  |


### TunedValues



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tunedValues** | ** | *(uuuu)* |  |


### RegisterDumpStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **registerDumpStatus** | ** | *u* |  |


### TouchSimulationStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **touchSimulationStatus** | ** | *u* |  |


### SpreadSpectrumStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **spreadSpectrumStatus** | ** | *u* |  |


### CMLLevelStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cMLLevelStatus** | ** | *u* |  |

