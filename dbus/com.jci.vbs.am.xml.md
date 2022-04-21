
# Dbus interface API

**com.jci.vbs.am**


## Methods

### SetMute



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **muteType** | *in* | *y* |  |
| **rampTime** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### SetUnMute



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **muteType** | *in* | *y* |  |
| **rampTime** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### SourceSelect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **source1** | *in* | *s* |  |
| **source2** | *in* | *s* |  |
| **source3** | *in* | *s* |  |
| **sourceOff** | *in* | *s* |  |
| **cMU\_Audio\_Left** | *in* | *s* |  |
| **cMU\_Audio\_Right** | *in* | *s* |  |
| **return\_value** | *out* | *y* |  |


### SetVolume



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **volumeType** | *in* | *y* |  |
| **controlValue** | *in* | *u* |  |
| **volumeValue** | *in* | *i* |  |
| **volSrcGrp** | *in* | *s* |  |
| **return\_value** | *out* | *y* |  |


### SetAudioProfile



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **controlValue** | *in* | *y* |  |
| **audioProfileType** | *in* | *y* |  |
| **audioProfileValue** | *in* | *i* |  |
| **lastProfile** | *in* | *i* |  |
| **return\_value** | *out* | *y* |  |


### GetVolumeStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **volSrcGrp** | *in* | *s* |  |
| **retVolSrcGrp** | *out* | *s* |  |
| **volumeValue** | *out* | *i* |  |
| **return\_value** | *out* | *y* |  |


### GetEntertainmentMuteStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **entertainmentMuteStatus** | *out* | *y* |  |


### GetLastMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### SetLastMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **activeSource** | *in* | *s* |  |
| **prevSource** | *in* | *s* |  |
| **broadcastSource** | *in* | *s* |  |
| **return\_value** | *out* | *y* |  |


### GetAudioProfileStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **profileType** | *in* | *y* |  |
| **profileValue** | *out* | *i* |  |
| **return\_value** | *out* | *y* |  |


### GetMuteStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **muteType** | *in* | *y* |  |
| **muteValue** | *out* | *y* |  |
| **return\_value** | *out* | *y* |  |


### SetVolumeVolMgr



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **bthfVol** | *in* | *y* |  |
| **ringToneVol** | *in* | *y* |  |
| **naviVol** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### GetActiveSource



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ret\_ActiveSrc** | *out* | *s* |  |
| **ret\_InterruptSrc** | *out* | *s* |  |
| **return\_value** | *out* | *y* |  |



## Signals

### AudioProfileStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **audioProfileType** | *in* | *y* |  |
| **audioProfileValue** | *in* | *i* |  |


### MuteStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **muteType** | *in* | *y* |  |


### UnMuteStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **muteType** | *in* | *y* |  |


### SourceSelectResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **source1** | *in* | *s* |  |
| **source2** | *in* | *s* |  |
| **source3** | *in* | *s* |  |
| **sourceOff** | *in* | *s* |  |


### VolumeStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **volumeType** | *in* | *y* |  |
| **volSrcGrp** | *in* | *s* |  |
| **volumeValue** | *in* | *i* |  |


### TAUSourceChangeResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **srcChangeResp** | *in* | *(yy)* |  |


### EntertainmentMuteStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **entertainmentMuteStat** | *in* | *y* |  |


### LastModeStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **entertainmentMuteStatus** | *in* | *y* |  |
| **lastActiveSource** | *in* | *s* |  |
| **lastPrevSource** | *in* | *s* |  |
| **lastBroadcastSource** | *in* | *s* |  |
| **currentSource** | *in* | *s* |  |
| **cdStatus** | *in* | *y* |  |
| **cdDiskType** | *in* | *y* |  |
| **auxStatus** | *in* | *y* |  |

