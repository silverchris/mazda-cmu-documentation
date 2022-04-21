
# Dbus interface API

**com.jci.tds**


## Methods

### STM\_Set\_ProcessMode\_async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **processMode** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### STM\_GetTMIFile



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **mapID** | *in* | *i* |  |
| **fileInfo** | *out* | *(a(is))* |  |
| **return\_value** | *out* | *i* |  |


### ARTEXP\_HDStationExit\_async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **oldFrequency** | *in* | *d* |  |
| **return\_value** | *out* | *i* |  |


### ARTEXP\_HDStationEnter\_async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **newFrequency** | *in* | *d* |  |
| **return\_value** | *out* | *i* |  |


### ARTEXP\_HDSubStationExit\_async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### ARTEXP\_GetStationLogo\_async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **serviceNumber** | *in* | *u* |  |
| **frequency** | *in* | *d* |  |
| **return\_value** | *out* | *i* |  |


### ARTEXP\_GetAlbumArt\_async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **serviceNumber** | *in* | *u* |  |
| **frequency** | *in* | *d* |  |
| **lotId** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### ExecuteTestCase



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **testCaseID** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |



## Signals

### TMC8A



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **block1** | ** | *q* |  |
| **block2** | ** | *q* |  |
| **block3** | ** | *q* |  |
| **block4** | ** | *q* |  |


### STM\_TrafficEvent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **eventSignal** | ** | *u* |  |


### STM\_StationId



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **stationId** | ** | *u* |  |


### STM\_RemoveTmt



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | ** | *u* |  |


### ARTEXP\_StationLogo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **serviceNumber** | ** | *u* |  |
| **frequency** | ** | *d* |  |
| **fileExists** | ** | *b* |  |


### ARTEXP\_AlbumArt



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **serviceNumber** | ** | *u* |  |
| **frequency** | ** | *d* |  |
| **lotId** | ** | *u* |  |
| **fileExists** | ** | *b* |  |


### STM\_TileElapseTimeUpdate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **minsElapsed** | ** | *u* |  |

