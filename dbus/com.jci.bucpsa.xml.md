
# Dbus interface API

**com.jci.bucpsa**


## Methods

### GetReverseStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **reverseStatus** | *out* | *i* |  |


### DisplayCommand



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **command** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### GetDisplayMode\_async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **currentDisplayMode** | *out* | *u* |  |
| **return\_value** | *out* | *i* |  |


### GetDisplayMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **currentDisplayMode** | *out* | *u* |  |
| **return\_value** | *out* | *i* |  |


### SetPSMEnabled



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **psmEnabled** | *in* | *y* |  |
| **return\_value** | *out* | *i* |  |


### GetPSMInstalledStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **psmInstalled** | *out* | *y* |  |


### GetSteeringWheelLocation



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **currentSteeringWheelLocation** | *out* | *u* |  |



## Signals

### CommandResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cmdResponse** | ** | *u* |  |


### DisplayMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **currentDisplayMode** | ** | *u* |  |


### ReverseStatusChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **reverseStatus** | ** | *i* |  |


### PSMInstallStatusChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **psmInstalled** | ** | *y* |  |


### CameraType



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **currentCameraType** | ** | *u* |  |


### SteeringWheelLocation



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **currentSteeringWheelLocation** | ** | *u* |  |

