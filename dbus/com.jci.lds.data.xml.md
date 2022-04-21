
# Dbus interface API

**com.jci.lds.data**


## Methods

### GetPosition



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **positionAccuracy** | *out* | *i* |  |
| **uTCtime** | *out* | *t* |  |
| **latitude** | *out* | *d* |  |
| **longitude** | *out* | *d* |  |
| **altitude** | *out* | *i* |  |
| **heading** | *out* | *d* |  |
| **velocity** | *out* | *d* |  |
| **horizontalAccuracy** | *out* | *d* |  |
| **verticalAccuracy** | *out* | *d* |  |


### GetLastKnownPosition



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **uTCtime** | *out* | *t* |  |
| **latitude** | *out* | *d* |  |
| **longitude** | *out* | *d* |  |


### GetGPSFirmwareVersion



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **firmwareVersion** | *out* | *s* |  |


### GetSatelliteInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **satellitesInUse** | *out* | *i* |  |



## Signals

### GPSDiagnostics



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dTCId** | ** | *y* |  |
| **dTCAction** | ** | *y* |  |


### OneTimeDRDiagnostics



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dRUnitVersion** | ** | *s* |  |
| **antennaStatus** | ** | *i* |  |
| **gyroSelfTest** | ** | *b* |  |
| **accelSelfTest** | ** | *b* |  |
| **resetLearning** | ** | *b* |  |
| **saveLearning** | ** | *b* |  |


### PeriodicDRDiagnostics



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dRUnitStatus** | ** | *i* |  |
| **speedPulse** | ** | *i* |  |
| **reverse** | ** | *b* |  |
| **dRUnitMode** | ** | *i* |  |
| **gyroStatus** | ** | *i* |  |
| **accelStatus** | ** | *i* |  |

