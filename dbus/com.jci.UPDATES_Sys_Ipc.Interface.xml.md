
# Dbus interface API

**com.jci.UPDATES_Sys_Ipc.Interface**


## Methods

### Connect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_connId** | *in* | *u* |  |
| **out\_result** | *out* | *i* |  |
| **out\_connId** | *out* | *u* |  |


### Disconnect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_connId** | *in* | *u* |  |
| **out\_result** | *out* | *i* |  |
| **out\_connId** | *out* | *u* |  |


### IsPresentFailSafeOS



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_connId** | *in* | *u* |  |
| **out\_isPresent** | *out* | *b* |  |
| **out\_result** | *out* | *i* |  |
| **out\_connId** | *out* | *u* |  |


### GetPackageInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_connId** | *in* | *u* |  |
| **in\_upLocation** | *in* | *s* |  |
| **out\_name** | *out* | *s* |  |
| **out\_type** | *out* | *i* |  |
| **out\_subtype** | *out* | *i* |  |
| **out\_version** | *out* | *s* |  |
| **out\_compatible** | *out* | *b* |  |
| **out\_result** | *out* | *i* |  |
| **out\_connId** | *out* | *u* |  |


### ValidateUP



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_connId** | *in* | *u* |  |
| **in\_upLocation** | *in* | *s* |  |
| **out\_name** | *out* | *s* |  |
| **out\_type** | *out* | *i* |  |
| **out\_subtype** | *out* | *i* |  |
| **out\_version** | *out* | *s* |  |
| **out\_compatible** | *out* | *b* |  |
| **out\_result** | *out* | *i* |  |
| **out\_connId** | *out* | *u* |  |


### CancelValidate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_connId** | *in* | *u* |  |
| **out\_result** | *out* | *i* |  |
| **out\_connId** | *out* | *u* |  |


### InstallUP



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_connId** | *in* | *u* |  |
| **in\_upLocation** | *in* | *s* |  |
| **in\_installCtrlOpt** | *in* | *i* |  |
| **out\_result** | *out* | *i* |  |
| **out\_nextStepInfo\_type** | *out* | *i* |  |
| **out\_nextStepInfo\_subtype** | *out* | *i* |  |
| **out\_nextStepInfo\_point** | *out* | *i* |  |
| **out\_connId** | *out* | *u* |  |


### CancelInstall



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_connId** | *in* | *u* |  |
| **out\_result** | *out* | *i* |  |
| **out\_connId** | *out* | *u* |  |


### GetUpdateStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_connId** | *in* | *u* |  |
| **out\_state** | *out* | *i* |  |
| **out\_progress** | *out* | *u* |  |
| **out\_result** | *out* | *i* |  |
| **out\_connId** | *out* | *u* |  |



## Signals

### update\_status\_event



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **state** | ** | *i* |  |
| **progress** | ** | *u* |  |
| **result** | ** | *i* |  |
| **connId** | ** | *u* |  |

