
# Dbus interface API

**com.jci.audiosettings**


## Methods

### BLM\_GetSettingInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setting\_type** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### BLM\_SetVolume



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setting\_type** | *in* | *i* |  |
| **absolute** | *in* | *i* |  |
| **step** | *in* | *i* |  |
| **string\_to\_play** | *in* | *s* |  |
| **return\_value** | *out* | *i* |  |


### Exit



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### BLM\_Exit



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### BLM\_BeepPlay



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **beep\_type** | *in* | *i* |  |


### BLM\_BeepPlay\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **beep\_type** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### BLM\_BeepSet\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **beep\_type** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### BLM\_GetEnableDisableInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setting\_type** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |



## Signals

### BLM\_SettingInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setting\_type** | ** | *i* |  |
| **enabled** | ** | *i* |  |
| **currentstep** | ** | *i* |  |
| **min** | ** | *i* |  |
| **max** | ** | *i* |  |


### BLM\_VolumeLevel



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setting\_type** | ** | *i* |  |
| **absolute** | ** | *i* |  |
| **step** | ** | *i* |  |
| **currentstep** | ** | *i* |  |


### BLM\_EnableDisableSettingsType



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setting\_type** | ** | *i* |  |
| **status** | ** | *b* |  |

