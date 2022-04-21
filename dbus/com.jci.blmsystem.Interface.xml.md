
# Dbus interface API

**com.jci.blmsystem.Interface**


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


### GenericReboot



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **mode\_flags** | *in* | *i* |  |
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


### GetCurrentSystemState



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **system\_state** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### RegisterForStateTransitionAck



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **from\_state** | *in* | *u* |  |
| **to\_state** | *in* | *u* |  |
| **\_from\_state** | *out* | *u* |  |
| **\_to\_state** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### AcknowledgeStateTransition



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **from\_state** | *in* | *u* |  |
| **to\_state** | *in* | *u* |  |
| **\_from\_state** | *out* | *u* |  |
| **\_to\_state** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### UnregisterFromStateTransitionAck



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **from\_state** | *in* | *u* |  |
| **to\_state** | *in* | *u* |  |
| **\_from\_state** | *out* | *u* |  |
| **\_to\_state** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### RegisterForShutdownAck



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *out* | *i* |  |


### AcknowledgeShutdown



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *out* | *i* |  |


### UnregisterFromShutdownAck



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *out* | *i* |  |


### SignalSystemStateEvent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **event** | *in* | *i* |  |
| **event\_info** | *in* | *i* |  |
| **\_event** | *out* | *i* |  |
| **\_event\_info** | *out* | *i* |  |
| **status** | *out* | *i* |  |


### ReportTestDiagEntering



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *out* | *i* |  |


### ReportTestDiagExiting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *out* | *i* |  |


### ReportGuiAvailable



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *out* | *i* |  |


### GetFactoryResetNum



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **number** | *out* | *i* |  |


### ReportXMInstalled



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **value** | *in* | *i* |  |



## Signals

### NotifyStateTransition



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **current\_state** | ** | *u* |  |
| **target\_state** | ** | *u* |  |


### NotifyShutdown



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **generic\_reboot\_flags** | ** | *u* |  |


### NotifyAccChange



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **acc\_state** | ** | *i* |  |
| **system\_state** | ** | *u* |  |


### NotifySystemStateChange



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **old\_state** | ** | *u* |  |
| **current\_state** | ** | *u* |  |

