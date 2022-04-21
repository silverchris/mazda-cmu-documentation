
# Dbus interface API

**com.jci.cpp.power.Interface**


## Methods

### OpenConnection



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *out* | *i* |  |
| **unique\_connection\_id** | *out* | *u* |  |


### CloseConnection



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *out* | *i* |  |


### SafeShutDown



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *out* | *i* |  |


### SafeReboot



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *out* | *i* |  |


### FactoryReset



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *out* | *i* |  |


### GetCurrentAccStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **acc\_state** | *out* | *i* |  |
| **status** | *out* | *i* |  |



## Signals

### NotifyAccChange



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **acc\_state** | ** | *i* |  |

