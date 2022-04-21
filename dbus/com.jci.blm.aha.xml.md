
# Dbus interface API

**com.jci.blm.aha**


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


### ChangeClientPlaybackState



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **playbackState** | *in* | *y* |  |
| **contentId** | *out* | *t* |  |
| **playState** | *out* | *y* |  |
| **statusId** | *out* | *i* |  |


### SelectContentForPlayback



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **contentId** | *in* | *t* |  |
| **statusId** | *out* | *i* |  |


### SelectStationForPlayback



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **stationId** | *in* | *t* |  |
| **playbackFromBegin** | *in* | *y* |  |
| **statusId** | *out* | *i* |  |


### TimeShiftContent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **nOSecondsToTimeShift** | *in* | *n* |  |
| **statusId** | *out* | *i* |  |


### PerformActionVoteLike



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **contentId** | *in* | *t* |  |
| **statusId** | *out* | *i* |  |


### PerformActionRetweet



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **contentId** | *in* | *t* |  |
| **statusId** | *out* | *i* |  |


### PerformActionTweetCurrentLocation



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **statusId** | *out* | *i* |  |


### PerformActionVoteDislike



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **contentId** | *in* | *t* |  |
| **statusId** | *out* | *i* |  |


### PerformActionUnvote



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **contentId** | *in* | *t* |  |
| **statusId** | *out* | *i* |  |


### PerformActionUploadCurrentLocationToFacebook



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **statusId** | *out* | *i* |  |


### PerformActionLogNavigate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **contentId** | *in* | *t* |  |
| **statusId** | *out* | *i* |  |


### PerformActionLogCallAction



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **contentId** | *in* | *t* |  |
| **statusId** | *out* | *i* |  |


### RecordingStart



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **maxRecordingTime** | *in* | *u* |  |
| **statusId** | *out* | *i* |  |


### RecordingCancel



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **statusId** | *out* | *i* |  |


### RecordingPost



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **statusId** | *out* | *i* |  |



## Signals

### StatusUpdate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |
| **status** | ** | *u* |  |
| **notifyConnectionLostFlag** | ** | *y* |  |


### RecordingCancelled



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |


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

