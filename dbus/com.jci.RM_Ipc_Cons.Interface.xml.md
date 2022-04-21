
# Dbus interface API

**com.jci.RM_Ipc_Cons.Interface**


## Methods

### Connect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_consPID** | *in* | *u* |  |
| **in\_consName** | *in* | *s* |  |
| **in\_consConn** | *in* | *u* |  |
| **in\_consContext** | *in* | *u* |  |
| **in\_seqId** | *in* | *u* |  |
| **out\_result** | *out* | *i* |  |
| **out\_consPID** | *out* | *u* |  |
| **out\_consName** | *out* | *s* |  |
| **out\_consConn** | *out* | *u* |  |
| **out\_consContext** | *out* | *u* |  |
| **out\_seqId** | *out* | *u* |  |


### Disconnect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_consPID** | *in* | *u* |  |
| **in\_consName** | *in* | *s* |  |
| **in\_consConn** | *in* | *u* |  |
| **in\_consContext** | *in* | *u* |  |
| **in\_seqId** | *in* | *u* |  |
| **out\_result** | *out* | *i* |  |
| **out\_consPID** | *out* | *u* |  |
| **out\_consName** | *out* | *s* |  |
| **out\_consConn** | *out* | *u* |  |
| **out\_consContext** | *out* | *u* |  |
| **out\_seqId** | *out* | *u* |  |


### AcquireResource



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_resName** | *in* | *s* |  |
| **in\_action** | *in* | *i* |  |
| **in\_consName** | *in* | *s* |  |
| **in\_consConn** | *in* | *u* |  |
| **in\_consContext** | *in* | *u* |  |
| **in\_seqId** | *in* | *u* |  |
| **out\_resName** | *out* | *s* |  |
| **out\_result** | *out* | *i* |  |
| **out\_action** | *out* | *i* |  |
| **out\_consName** | *out* | *s* |  |
| **out\_consConn** | *out* | *u* |  |
| **out\_consContext** | *out* | *u* |  |
| **out\_seqId** | *out* | *u* |  |


### ReleaseResource



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_resName** | *in* | *s* |  |
| **in\_action** | *in* | *i* |  |
| **in\_consName** | *in* | *s* |  |
| **in\_consConn** | *in* | *u* |  |
| **in\_consContext** | *in* | *u* |  |
| **in\_seqId** | *in* | *u* |  |
| **out\_resName** | *out* | *s* |  |
| **out\_result** | *out* | *i* |  |
| **out\_action** | *out* | *i* |  |
| **out\_consName** | *out* | *s* |  |
| **out\_consConn** | *out* | *u* |  |
| **out\_consContext** | *out* | *u* |  |
| **out\_seqId** | *out* | *u* |  |


### GetResourceInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_resName** | *in* | *s* |  |
| **in\_consName** | *in* | *s* |  |
| **in\_consConn** | *in* | *u* |  |
| **in\_consContext** | *in* | *u* |  |
| **in\_seqId** | *in* | *u* |  |
| **out\_resName** | *out* | *s* |  |
| **in\_attributes** | *out* | *(a(siay))* |  |
| **out\_status** | *out* | *i* |  |
| **out\_result** | *out* | *i* |  |
| **out\_consName** | *out* | *s* |  |
| **out\_consConn** | *out* | *u* |  |
| **out\_consContext** | *out* | *u* |  |
| **out\_seqId** | *out* | *u* |  |


### SubscribeForEvent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_resName** | *in* | *s* |  |
| **in\_status** | *in* | *i* |  |
| **in\_consName** | *in* | *s* |  |
| **in\_consConn** | *in* | *u* |  |
| **in\_consContext** | *in* | *u* |  |
| **in\_seqId** | *in* | *u* |  |
| **out\_resName** | *out* | *s* |  |
| **out\_subscrStatus** | *out* | *i* |  |
| **out\_result** | *out* | *i* |  |
| **out\_currStatus** | *out* | *i* |  |
| **out\_consName** | *out* | *s* |  |
| **out\_consConn** | *out* | *u* |  |
| **out\_consContext** | *out* | *u* |  |
| **out\_seqId** | *out* | *u* |  |


### UnsubscribeFromEvent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **in\_resName** | *in* | *s* |  |
| **in\_status** | *in* | *i* |  |
| **in\_consName** | *in* | *s* |  |
| **in\_consConn** | *in* | *u* |  |
| **in\_consContext** | *in* | *u* |  |
| **in\_seqId** | *in* | *u* |  |
| **out\_resName** | *out* | *s* |  |
| **out\_status** | *out* | *i* |  |
| **out\_result** | *out* | *i* |  |
| **out\_consName** | *out* | *s* |  |
| **out\_consConn** | *out* | *u* |  |
| **out\_consContext** | *out* | *u* |  |
| **out\_seqId** | *out* | *u* |  |



## Signals

### acquire\_resource\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **resName** | ** | *s* |  |
| **result** | ** | *i* |  |
| **action** | ** | *i* |  |
| **consName** | ** | *s* |  |
| **consConn** | ** | *u* |  |
| **consContext** | ** | *u* |  |
| **seqId** | ** | *u* |  |


### release\_command\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **resName** | ** | *s* |  |
| **consName** | ** | *s* |  |
| **consConn** | ** | *u* |  |
| **consContext** | ** | *u* |  |


### resource\_event\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **resName** | ** | *s* |  |
| **attributes** | ** | *(a(siay))* |  |
| **status** | ** | *i* |  |
| **consName** | ** | *s* |  |
| **consConn** | ** | *u* |  |
| **consContext** | ** | *u* |  |

