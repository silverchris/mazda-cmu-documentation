
# Dbus interface API

**com.jci.RM_Ipc_Prov.Interface**


## Methods

### Connect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_provPID** | *in* | *u* |  |
| **in\_provName** | *in* | *s* |  |
| **in\_provConn** | *in* | *u* |  |
| **in\_provContext** | *in* | *u* |  |
| **in\_seqId** | *in* | *u* |  |
| **out\_result** | *out* | *i* |  |
| **out\_provPID** | *out* | *u* |  |
| **out\_provName** | *out* | *s* |  |
| **out\_provConn** | *out* | *u* |  |
| **out\_provContext** | *out* | *u* |  |
| **out\_seqId** | *out* | *u* |  |


### PreConnect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_provPID** | *in* | *u* |  |
| **in\_provName** | *in* | *s* |  |
| **out\_result** | *out* | *i* |  |
| **return\_value** | *out* | *i* |  |


### Disconnect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_force** | *in* | *b* |  |
| **in\_provPID** | *in* | *u* |  |
| **in\_provName** | *in* | *s* |  |
| **in\_provConn** | *in* | *u* |  |
| **in\_provContext** | *in* | *u* |  |
| **in\_seqId** | *in* | *u* |  |
| **out\_result** | *out* | *i* |  |
| **out\_provPID** | *out* | *u* |  |
| **out\_provName** | *out* | *s* |  |
| **out\_provConn** | *out* | *u* |  |
| **out\_provContext** | *out* | *u* |  |
| **out\_seqId** | *out* | *u* |  |


### RegisterResource



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_resName** | *in* | *s* |  |
| **in\_attributes** | *in* | *(a(siay))* |  |
| **in\_supportActDeactLogic** | *in* | *b* |  |
| **in\_provName** | *in* | *s* |  |
| **in\_provConn** | *in* | *u* |  |
| **in\_provContext** | *in* | *u* |  |
| **in\_seqId** | *in* | *u* |  |
| **out\_resName** | *out* | *s* |  |
| **out\_result** | *out* | *i* |  |
| **out\_provName** | *out* | *s* |  |
| **out\_provConn** | *out* | *u* |  |
| **out\_provContext** | *out* | *u* |  |
| **out\_seqId** | *out* | *u* |  |


### UnregisterResource



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_resName** | *in* | *s* |  |
| **in\_attributes** | *in* | *(a(siay))* |  |
| **in\_force** | *in* | *b* |  |
| **in\_provName** | *in* | *s* |  |
| **in\_provConn** | *in* | *u* |  |
| **in\_provContext** | *in* | *u* |  |
| **in\_seqId** | *in* | *u* |  |
| **out\_resName** | *out* | *s* |  |
| **out\_result** | *out* | *i* |  |
| **out\_provName** | *out* | *s* |  |
| **out\_provConn** | *out* | *u* |  |
| **out\_provContext** | *out* | *u* |  |
| **out\_seqId** | *out* | *u* |  |


### ActivateResourceResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_resName** | *in* | *s* |  |
| **in\_attributes** | *in* | *(a(siay))* |  |
| **in\_result** | *in* | *i* |  |
| **in\_provName** | *in* | *s* |  |
| **in\_provConn** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### DeactivateResourceResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_resName** | *in* | *s* |  |
| **in\_attributes** | *in* | *(a(siay))* |  |
| **in\_result** | *in* | *i* |  |
| **in\_provName** | *in* | *s* |  |
| **in\_provConn** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |



## Signals

### activate\_resource\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **resName** | ** | *s* |  |
| **provName** | ** | *s* |  |
| **provConn** | ** | *u* |  |
| **provContext** | ** | *u* |  |


### deactivate\_resource\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **resName** | ** | *s* |  |
| **provName** | ** | *s* |  |
| **provConn** | ** | *u* |  |
| **provContext** | ** | *u* |  |

