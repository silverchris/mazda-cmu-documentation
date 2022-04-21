
# Dbus interface API

**com.jci.navi2IHU.HUDSettings**


## Methods

### GetHUDIsInstalled



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hUDInstalled** | *out* | *b* |  |


### GetHUDIsInstalled\_async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hUDInstalled** | *out* | *b* |  |


### SetHUDSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hUDSettingType** | *in* | *i* |  |
| **hUDSettingValue** | *in* | *i* |  |


### SetHUDSetting\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hUDSettingType** | *in* | *i* |  |
| **hUDSettingValue** | *in* | *i* |  |


### GetHUDSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hUDSettingType** | *in* | *i* |  |
| **hUDSettingValue** | *out* | *i* |  |


### ResetHUDSettings




### GetHUDControlAllowed



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **bAllowed** | *out* | *i* |  |



## Signals

### HUDInstalledChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hUDInstalled** | ** | *b* |  |


### SetHUDSettingFailed



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hUDSettingType** | ** | *i* |  |
| **err** | ** | *i* |  |


### HUDControlAllowed



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **bAllowed** | ** | *b* |  |


### HUDSettingChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hUDSettingType** | ** | *i* |  |
| **value** | ** | *i* |  |

