
# Dbus interface API

**com.jci.blm.stitcher**


## Methods

### Connect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **statusId** | *out* | *i* |  |
| **sessionId** | *out* | *u* |  |
| **keepConnected** | *out* | *b* |  |


### Disconnect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **statusId** | *out* | *i* |  |


### Command



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **command** | *in* | *y* |  |
| **groupType** | *in* | *y* |  |
| **groupId** | *in* | *t* |  |
| **statusId** | *out* | *i* |  |


### Rate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **groupType** | *in* | *y* |  |
| **id** | *in* | *t* |  |
| **rate** | *in* | *y* |  |
| **isRelative** | *in* | *b* |  |
| **statusId** | *out* | *i* |  |



## Signals

### Connected



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |
| **keepConnected** | ** | *b* |  |


### Disconnected



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |
| **reasonId** | ** | *y* |  |

