
# Dbus interface API

**com.jci.obs.aha.svc**


## Methods

### ConnectUsingPseudoTerminal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pseudoTerminal** | *in* | *s* |  |
| **sessionName** | *in* | *s* |  |
| **vehicleInfo** | *in* | *(ssssss)* |  |
| **shoutFormat** | *in* | *y* |  |
| **status** | *out* | *i* |  |
| **sessionId** | *out* | *u* |  |


### Disconnect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **reasonId** | *in* | *u* |  |
| **status** | *out* | *i* |  |


### ChangeClientPlaybackState



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **playbackState** | *in* | *y* |  |
| **contentId** | *out* | *t* |  |
| **playState** | *out* | *y* |  |
| **status** | *out* | *i* |  |


### SelectContentForPlayback



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **contentId** | *in* | *t* |  |
| **status** | *out* | *i* |  |


### SelectStationForPlayback



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **stationId** | *in* | *t* |  |
| **playbackFromBegin** | *in* | *y* |  |
| **status** | *out* | *i* |  |


### TimeShiftContent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **nOSecondsToTimeShift** | *in* | *n* |  |
| **status** | *out* | *i* |  |


### PerformAction



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **actionId** | *in* | *u* |  |
| **contentId** | *in* | *t* |  |
| **status** | *out* | *i* |  |


### PostNewRecording



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **file** | *in* | *s* |  |
| **status** | *out* | *i* |  |



## Signals
