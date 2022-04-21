
# Dbus interface API

**com.jci.obs.stitcher.svc**


## Methods

### ConnectUsingPseudoTerminal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pseudoTerminal** | *in* | *s* |  |
| **sessionName** | *in* | *s* |  |
| **status** | *out* | *i* |  |
| **sessionId** | *out* | *u* |  |


### Disconnect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **reasonId** | *in* | *u* |  |
| **status** | *out* | *i* |  |


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
| **type** | *in* | *y* |  |
| **id** | *in* | *t* |  |
| **rate** | *in* | *y* |  |
| **isRelative** | *in* | *b* |  |
| **statusId** | *out* | *i* |  |



## Signals
