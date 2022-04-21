
# Dbus interface API

**com.jci.btmusic**


## Methods

### StartStreaming



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### StopStreaming



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### StreamingAudioCmd



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **commandType** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### GetTrackInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### BrowseFolderUp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **folderType** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### BrowseFolderDown



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **index** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### GetBrowseItemTitleForFolder



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **itemStartIndex** | *in* | *u* |  |
| **itemEndIndex** | *in* | *u* |  |
| **requestedPage** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### GetNowPlayListTitleForFile



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **itemStartIndex** | *in* | *u* |  |
| **itemEndIndex** | *in* | *u* |  |
| **requestedPage** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### PlayBrowseItem



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playScope** | *in* | *u* |  |
| **playItemId** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### SetLanguage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sys\_lang** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |



## Signals

### StreamingStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **streamStatus** | *in* | *u* |  |


### StreamingAudioCmdStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **commandType** | *in* | *u* |  |
| **commandStatus** | *in* | *u* |  |


### StreamingPlayerStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playerStatus** | *in* | *u* |  |
| **reason** | *in* | *u* |  |


### TrackInformation



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **trackInfo** | *in* | *(ay)* |  |


### DeviceBatteryIndicator



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **batteryStrength** | *in* | *u* |  |


### BusyReason



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **busyReason** | *in* | *u* |  |


### TrackChangeIndicator




### TrackPositionIndicator



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **elapsedTime** | *in* | *i* |  |


### NowPlayingChangeIndicator




### SettingsStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **settingType** | *in* | *u* |  |
| **settingValue** | *in* | *u* |  |
| **settingStatus** | *in* | *u* |  |


### PlayerSettingsInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playerSetting** | *in* | *(ay)* |  |


### FolderBrowseItemTitleResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **foldertitleResponse** | *in* | *(ay)* |  |


### BrowseNowPlayingTitleResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **nowPlayingTitleResponse** | *in* | *(ay)* |  |


### BrowseFolderResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **browseFolderResp** | *in* | *(ay)* |  |


### BrowseStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **browseStatus** | *in* | *u* |  |


### BrowseConnStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **browseConnStatus** | *in* | *u* |  |


### NowPlayingInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **nowPlayingIndex** | *in* | *u* |  |
| **nowPlayingTotalCount** | *in* | *u* |  |


### MusicProfileSupported



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **musicProfile** | *in* | *u* |  |

