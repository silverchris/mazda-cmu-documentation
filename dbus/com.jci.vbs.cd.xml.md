
# Dbus interface API

**com.jci.vbs.cd**


## Methods

### PlayCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### PauseCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### NextTrackCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### PreviousTrackCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### FastForwardCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### FastReverseCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### EjectCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### FolderUpCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### FolderDownCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### UpdateDiscCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### ScanCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### SlowForwardCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### SlowRewindCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### GotoMenuCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### GotoPlayerMenuCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### RepeatCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **trackFolderRepeat** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### RandomCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **trackFolderRandom** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### SubtitleSettingCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **subtitleSetting** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### DirectTrackSeekCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **directTrackSeek** | *in* | *u* |  |
| **return\_value** | *out* | *y* |  |


### MultiAngleCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **multiAngle** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### DVDMenuOperationCDCommand



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dVDMenuOperationCmd** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### PlaybackJumpCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playbackJump** | *in* | *y* |  |
| **playbackJumpPercentage** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### DVDAspectRatioChange



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dVDAspectRatioValue** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### TrackFolderListRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **listDirectoryType** | *in* | *y* |  |
| **listTypeReq** | *in* | *y* |  |
| **folderIndexReq** | *in* | *q* |  |
| **indexReqStart** | *in* | *q* |  |
| **indexReqStop** | *in* | *q* |  |
| **return\_value** | *out* | *y* |  |


### GetMetaDataCDRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### GetCDDVDReadyStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_cddvdStatus** | *out* | *y* |  |


### GetCDDVDStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **statusType** | *in* | *y* |  |
| **metadataType** | *in* | *y* |  |
| **return\_StatusValue** | *out* | *y* |  |


### GetOperationStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_oprStatus** | *out* | *y* |  |


### GetDiscType



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_discType** | *out* | *y* |  |


### GetCDDTVStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **statusType** | *in* | *y* |  |
| **return\_statusValue** | *out* | *y* |  |


### GetDVDConfigStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_dvdConfigStatus** | *out* | *y* |  |


### GetMaxAllowedMovieRatingRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *q* |  |


### DVDParentalCntlNotification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **parentalCntlType** | *in* | *y* |  |
| **parentalCntlVal** | *in* | *q* |  |
| **return\_value** | *out* | *y* |  |


### GetAllCDDVDStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### TouchPanelID



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **touchXCoord** | *in* | *q* |  |
| **touchYCoord** | *in* | *q* |  |
| **return\_status** | *out* | *y* |  |


### TVControlRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **controlCmdType** | *in* | *y* |  |
| **controlCmdVal** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### DTV\_VideoSource\_Change\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **videoSrcChange** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### GetCDTVRoutineTestRespStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_routineStatus** | *out* | *y* |  |


### RoutineTest\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **routineTestType** | *in* | *y* |  |
| **routineTestVal** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |



## Signals

### cdDVDStatusResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cdDvdStatus** | *in* | *(yay)* |  |


### cdDTVStatusResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cdDtvStatusType** | *in* | *y* |  |
| **cdDtvStatusValue** | *in* | *y* |  |


### metaDataResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **metaDataResp** | *in* | *(ayayayayayayay)* |  |


### trackPlayStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **trackStatus** | *in* | *(qyyyyyyy)* |  |


### cdSourceChangeResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **onTargetChngResp** | *in* | *y* |  |
| **offTargetChngResp** | *in* | *y* |  |


### cdDvdConfigStatusResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cdDvdConfigStatusResp** | *in* | *y* |  |


### cdTrackFolderList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **trackFolderListInfo** | *in* | *(yyqqay)* |  |


### cdDvdFolderContents



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **folderContents** | *in* | *(yqqq)* |  |


### cdDvdVersionResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ccdDvdVersion** | *in* | *(ayay)* |  |


### cdDvdCurrTrackFoldernum



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **currTrackFoldernum** | *in* | *y* |  |


### GetAllCDVDStatusResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cDVDStat** | ** | *(ayyyyyyyyyyyyyyay)* |  |


### DTV\_VideoSource\_Change\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **videoSrcChange** | *in* | *y* |  |


### DTVSourceChangeResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **onTargetChngResp** | *in* | *y* |  |
| **offTargetChngResp** | *in* | *y* |  |


### DTVReady



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dTVReady** | *in* | *y* |  |


### BeepControlDTVResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **beepControlResponse** | *in* | *y* |  |


### BeepControlDVDResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **beepControlResponse** | *in* | *y* |  |


### DTVMaxAllowedMovieRating



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **maxAllowedMovieRatingStatusValue** | *in* | *q* |  |


### DTVRoutineTestResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cdDtvConfigStatusResp** | *in* | *y* |  |

