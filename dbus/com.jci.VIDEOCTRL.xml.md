
# Dbus interface API

**com.jci.VIDEOCTRL**


## Methods

### SelectVideoDevice



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **device** | *in* | *i* |  |
| **status** | *out* | *i* |  |


### GetCapability



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *out* | *(b(ii)(ii)(ii)(ii)i(iiii))* |  |


### TestVideoStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **device** | *in* | *i* |  |
| **videoStatus** | *out* | *i* |  |
| **outDevice** | *out* | *i* |  |


### GetVideoStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **device** | *in* | *i* |  |
| **videoStatus** | *out* | *i* |  |
| **outDevice** | *out* | *i* |  |


### GetAdjustments



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **adjustments** | *out* | *(iiii)* |  |


### SetDeviceInstalled



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **device** | *in* | *i* |  |
| **installed** | *in* | *i* |  |


### SetContrast



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **contrast** | *in* | *i* |  |
| **newContrast** | *out* | *i* |  |


### SetBrightness



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **brightness** | *in* | *i* |  |
| **newBrightness** | *out* | *i* |  |


### SetTint



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tint** | *in* | *i* |  |
| **newTint** | *out* | *i* |  |


### SetColor



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **color** | *in* | *i* |  |
| **newColor** | *out* | *i* |  |


### DeselectDevice



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **device** | *in* | *i* |  |
| **status** | *out* | *i* |  |


### SetOutputViewport



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **device** | *in* | *i* |  |
| **x** | *in* | *i* |  |
| **y** | *in* | *i* |  |
| **width** | *in* | *i* |  |
| **height** | *in* | *i* |  |
| **status** | *out* | *i* |  |


### ResetAdjustments



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *out* | *i* |  |



## Signals

### VideoSignalChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **videoSignal** | ** | *i* |  |
| **device** | ** | *i* |  |


### onSettingsChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **adjustments** | ** | *(a(iiii))* |  |


### CameraOffSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **bucStatus** | ** | *i* |  |
| **dvdStatus** | ** | *i* |  |
| **tvStatus** | ** | *i* |  |
| **cpStatus** | ** | *i* |  |
| **aaStatus** | ** | *i* |  |

