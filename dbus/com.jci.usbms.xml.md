
# Dbus interface API

**com.jci.usbms**


## Methods

### BrowseContext



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **browseContext** | *in* | *(u(a(iuuui))suu)* |  |
| **browseContextReply** | *out* | *(ua(sui)u)* |  |


### GetBrowseFolderInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **getBrowseFolderInfo** | *in* | *(u(a(iuuui))u)* |  |
| **getBrowseFolderInfoReply** | *out* | *(ussu)* |  |


### PauseResume



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pauseResume** | *in* | *(u)* |  |
| **pauseResumeReply** | *out* | *(u)* |  |


### PlayResume



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playResume** | *in* | *(ui)* |  |
| **playResumeReply** | *out* | *((iuuui)iiissu(ussss)(uu)u)* |  |


### PlayContext



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playContext** | *in* | *(u(iuuui)su)* |  |
| **playContextReply** | *out* | *(iiissu(ussss)(uu)i)* |  |


### StopPlayback



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **stopPlayback** | *in* | *(u)* |  |
| **stopPlaybackReply** | *out* | *(u)* |  |


### GetAlbumArt



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **getAlbumArt** | *in* | *(uu)* |  |
| **getAlbumArtReply** | *out* | *(suu)* |  |


### PlayerSeek



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playerSeek** | *in* | *(uiu)* |  |
| **playerSeekReply** | *out* | *(i)* |  |


### PlayTrackControl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playTrackCtrl** | *in* | *(uiu)* |  |
| **playTrackCtrlReply** | *out* | *(i)* |  |


### SetPlayerSettings



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setPlayerSettings** | *in* | *(uii)* |  |
| **setPlayerSettingsReply** | *out* | *(i)* |  |


### GetStorageDevicesList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **getStorageDevListReply** | *out* | *(a(uussii(a((uiiuu)u)u)))* |  |


### GetPlayTrackInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **getPlayTrackInfoReply** | *out* | *((ussss)i)* |  |


### MoreLikeThis



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **moreLikeThis** | *in* | *(u)* |  |
| **moreLikeThisReply** | *out* | *((iuuui)su)* |  |


### GetSongsInfoList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **getSongsInfoList** | *in* | *(uuu)* |  |
| **getSongsInfoListReply** | *out* | *((a(susususu))u)* |  |


### SetLanguage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setLanguage** | *in* | *(u)* |  |
| **setLanguageReply** | *out* | *(i)* |  |


### GetAlphabet



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **getAlphabet** | *in* | *(u(a(iuuui)))* |  |
| **getAlphabetReply** | *out* | *(a(uis))* |  |


### GetTaggingInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **getTaggingInfo** | *in* | *(u)* |  |
| **getTaggingInfoReply** | *out* | *(ttuqyyu)* |  |


### iPodSendTag



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iPodSendTag** | *in* | *(u(ay)q)* |  |
| **iPodSendTagReply** | *out* | *(u)* |  |


### SaveData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **saveDataReply** | *out* | *(i)* |  |



## Signals

### StorageAttached



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **storageAttached** | *in* | *((uussii(a((uiiuu)u)u))u)* |  |


### StorageDetached



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **storageDetached** | *in* | *(u)* |  |


### SyncEvent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **syncEvent** | *in* | *(uiiuu)* |  |


### DbUpdate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dbUpdate** | *in* | *(uiu)* |  |


### TrackChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **trackChanged** | *in* | *(ussu(ussss)(uu))* |  |


### PlayComplete



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playComplete** | *in* | *(i)* |  |


### PlaybackTime



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playbackTime** | *in* | *(uu)* |  |


### DeviceError



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **deviceError** | *in* | *(ui)* |  |


### PlayerStateChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playerStateChanged** | *in* | *(uiissu(ussss)(uu))* |  |


### PlaybackSettingsChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playbackSettingsChanged** | *in* | *(uii)* |  |


### AlbumArtReady



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **albumArtReady** | *in* | *(u)* |  |


### Ping



