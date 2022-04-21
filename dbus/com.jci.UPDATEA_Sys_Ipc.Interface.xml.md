
# Dbus interface API

**com.jci.UPDATEA_Sys_Ipc.Interface**


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


### GetVersion



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_connId** | *in* | *u* |  |
| **in\_versionType** | *in* | *i* |  |
| **out\_versionType** | *out* | *i* |  |
| **out\_version** | *out* | *s* |  |
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


### SearchForAvailableUPs



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_connId** | *in* | *u* |  |
| **out\_packageInfo** | *out* | *(a(sis))* |  |
| **out\_result** | *out* | *i* |  |
| **out\_connId** | *out* | *u* |  |


### CancelSearchForUPs



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_connId** | *in* | *u* |  |
| **out\_result** | *out* | *i* |  |
| **out\_connId** | *out* | *u* |  |


### ValidateAndDownloadUP



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_connId** | *in* | *u* |  |
| **in\_upLocation** | *in* | *s* |  |
| **out\_result** | *out* | *i* |  |
| **out\_connId** | *out* | *u* |  |


### CancelValidAndDwnld



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


### RebootBoard



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_connId** | *in* | *u* |  |
| **out\_result** | *out* | *i* |  |
| **out\_connId** | *out* | *u* |  |



## Signals

### available\_ups\_event



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **packageInfo** | ** | *(a(sis))* |  |
| **connId** | ** | *u* |  |


### available\_autoupdate\_event



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **packageInfo** | ** | *(sis)* |  |
| **connId** | ** | *u* |  |


### update\_status\_event



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **state** | ** | *i* |  |
| **progress** | ** | *u* |  |
| **result** | ** | *i* |  |
| **connId** | ** | *u* |  |

