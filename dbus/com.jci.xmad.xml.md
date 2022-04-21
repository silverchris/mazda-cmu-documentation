
# Dbus interface API

**com.jci.xmad**


## Methods

### GetScanSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetInstallStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetSignalQuality



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetAntennaState



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetFirstXMFavAddition



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetTuneStartSettingStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetFavListID



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetActiveCategory



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetSessionLockStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetParentalLockInitSetupStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetIsTuneScanSettingUsedBefore



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetTuneScanContentAvailabilityInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetBTConnectionStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetIRBufferCapacity



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetESN



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetSmartFavChannelsCount



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetTuneMixActiveStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetTuneMixCount



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetTuneStartFirstTimeUsage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetTuneMixDetails



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tunemix\_Id** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### GetSportFlashActiveStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetSportFlashFreq



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetSportFlashFirstTimeUsage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetTWReportActiveStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetTWReportFreq



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetTWReportFirstTimeUsage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetNearestCityName



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetSubscriptionUpdateStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### SourceChangeToXM



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Seek



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **seek\_type** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### DirectTune



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **id** | *in* | *u* |  |
| **tuneToServiceID** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### ChangeCategory



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ch\_list\_type** | *in* | *u* |  |
| **category\_id** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### ScanSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **scan\_type** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### ScanReq



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **scan\_req** | *in* | *(uu)* |  |
| **return\_value** | *out* | *i* |  |


### TuneStartSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tune\_start\_enable** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### EditSmartFavList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **chanID** | *in* | *u* |  |
| **isSFChannel** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### SessionLock



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **session\_lock\_req** | *in* | *(ub)* |  |
| **return\_value** | *out* | *i* |  |


### ChannelLock



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **channel\_lock\_req** | *in* | *(uu)* |  |
| **return\_value** | *out* | *i* |  |


### RequestPinResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pin\_info** | *in* | *(u(yyyy))* |  |
| **return\_value** | *out* | *i* |  |


### ChangePinReq



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pin\_type** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### PlayControl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playControl** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### SeekTime



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **durationInSec** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### SeekTrack



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **direction** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### CreateTuneMix



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **create\_tunemix\_req** | *in* | *(a(usb))* |  |
| **return\_value** | *out* | *i* |  |


### EditTuneMix



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **edit\_tunemix\_req** | *in* | *(ua(usb))* |  |
| **return\_value** | *out* | *i* |  |


### RenameTuneMix



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **rename\_tunemix\_req** | *in* | *(us)* |  |
| **return\_value** | *out* | *i* |  |


### RemoveTuneMix



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tunemix\_id** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### TuneStartUsed



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### FirstFavoriteAdded



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### TuneScanUsed



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### ExitTuneMix



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### TuneFeaturedFav



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tune\_featured\_fav** | *in* | *(uu)* |  |
| **return\_value** | *out* | *i* |  |


### SportFlashFirstTimeUsed



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### SetSportsFlashFrequency



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **flashFreq** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### EnableSportFlashAlert



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **enableAlert** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### SelectSportsFlashTeam



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **leagueId** | *in* | *u* |  |
| **teamId** | *in* | *u* |  |
| **favorite** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### MoveSportsFlashTeam



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **refLeagueID ** | *in* | *u* |  |
| **leagueID** | *in* | *u* |  |
| **refTeamId ** | *in* | *u* |  |
| **teamId** | *in* | *u* |  |
| **moveType** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### DismissFlashAlert



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **channelID** | *in* | *u* |  |
| **flashEventID** | *in* | *u* |  |
| **flashAlertType** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### PlayFlashAlert



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **flashEventID** | *in* | *u* |  |
| **flashAlertType** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### TurnOffAlert



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **flashAlertType** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### AbortFlashAlert



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **flashEventID** | *in* | *u* |  |
| **flashAlertType** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### ReplayFlashAlert



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **flashEventID** | *in* | *u* |  |
| **flashAlertType** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### TWReportFirstTimeUsed



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### SetTWReportFrequency



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **twReportFreq** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### EnableTWReportAlert



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **enableTWReportAlert** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### SelectTWCity



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **selectTWCity** | *in* | *s* |  |
| **isNearestCity** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### SuspendAlertContextStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **suspendAlertContextRemoved** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### isValidChannelID



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **channelID** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### PlayFirstTuneMix



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetFlashAvailableStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **flashAlertType** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### SubscriptionUserAccept



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### PlayTuneGame



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **id\_h** | *in* | *u* |  |
| **id\_m** | *in* | *u* |  |
| **id\_l** | *in* | *u* |  |
| **tuneToServiceID** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### SubscriptionUpdateConf



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |



## Signals

### SourceChangeStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **source\_change\_status** | *in* | *u* |  |


### TuneStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tune\_state** | *in* | *(uu)* |  |


### installStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **install\_status** | *in* | *u* |  |


### SignalQuality



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **signal\_quality\_state** | *in* | *u* |  |


### AntennaState



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **antenna\_state** | *in* | *u* |  |


### ChannelDescriptionServiceStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **channel\_description\_status** | *in* | *b* |  |


### TuneStartSettingStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tune\_start\_status** | *in* | *b* |  |


### LockPinStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **lock\_pin\_status** | *in* | *u* |  |


### CurrentTunedChannel



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **current\_channel\_info** | *in* | *(uuayu)* |  |


### ChannelStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **channel\_state** | *in* | *(ubuuu)* |  |


### ActiveCategory



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **active\_category\_info** | *in* | *(uuuuu)* |  |


### ScanStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **scan\_status** | *in* | *(uu)* |  |


### ScanReqStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **error\_status** | *in* | *u* |  |


### ScanSettingStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **scan\_type** | *in* | *u* |  |


### DirectTuneStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **direct\_tune\_status** | *in* | *(uu)* |  |


### ChannelListUpdateStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **listID** | *in* | *u* |  |
| **channelListSize** | *in* | *u* |  |
| **index** | *in* | *u* |  |
| **channelListInitialize** | *in* | *b* |  |
| **updateType** | *in* | *(bbbb)* |  |


### CategoryUpdate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **catID** | ** | *u* |  |
| **name** | ** | *s* |  |
| **updateType** | ** | *(bbb)* |  |


### RequestPin



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pin\_type** | *in* | *u* |  |


### RequestPinStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pin\_status** | *in* | *u* |  |


### ChannelLockStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **channel\_lock\_status** | *in* | *u* |  |


### SessionLockStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **session\_lock\_status** | *in* | *u* |  |


### ParentalLockInitSetupStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **init\_setup\_status** | *in* | *b* |  |


### SeekStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **seek\_status** | *in* | *(uu)* |  |


### EditSmartFavListStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **retChID** | *in* | *u* |  |
| **retIsSFChannel** | *in* | *b* |  |
| **raturn\_Status** | *in* | *u* |  |


### NotifyFirstXMFavAddition



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **first\_fav\_addition\_status** | *in* | *b* |  |


### NotifyFavListID



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fav\_list\_id** | *in* | *u* |  |


### TuneScanSettingFirstTimeUsage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **first\_time\_usage ** | *in* | *b* |  |


### TuneScanContentAvailabilityStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tune\_scan\_availability  ** | *in* | *b* |  |


### BTConnectionStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **bTConnected  ** | *in* | *b* |  |


### SubscriptionStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **subscription\_state** | *in* | *(uyuayay)* |  |


### IRBufferCapacityStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ir\_buffer\_state** | *in* | *(uu)* |  |


### PlayControlStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status ** | *in* | *u* |  |


### PlayBackStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **play\_back\_status** | *in* | *(uu)* |  |


### PlaybackTimeStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playback\_time** | *in* | *(uuu)* |  |


### SeekTimeStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status ** | *in* | *u* |  |


### PlaybackOffsetIndication



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playBackOffset ** | *in* | *u* |  |


### ESNInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **esn\_val ** | *in* | *s* |  |


### TracksBeforeAfter



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tracks\_info** | *in* | *(uu)* |  |


### TuneMixActive



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tunemix\_state\_info** | *in* | *(buay)* |  |


### PlaybackTrackTimeStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playback\_track\_time** | *in* | *(uu)* |  |


### CreateTuneMixStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **create\_tunemix\_status** | *in* | *(ayuuu)* |  |


### EditTuneMixStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **edit\_tunemix\_status** | *in* | *(ayuuu)* |  |


### RenameTunemixStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **rename\_tunemix\_status** | *in* | *(su)* |  |


### RemoveTuneMixStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **remove\_tunemix\_status** | *in* | *(uu)* |  |


### TuneStartFirstTimeUsageStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **first\_time\_usage ** | *in* | *b* |  |


### SmartFavChannelsCount



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **channel\_count ** | *in* | *u* |  |


### TuneMixCount



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tunemix\_count ** | *in* | *u* |  |


### TuneMixDetails



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tunemix\_details** | *in* | *(ua(usb))* |  |


### TuneMixListUpdated



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tunemix\_count ** | *in* | *u* |  |


### TuneFeaturedFavStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tune\_featuedfav\_status** | *in* | *(uuuu)* |  |


### FeaturedFavListUpdated



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **list\_updated** | *in* | *(uay(bbb))* |  |


### SportFlashActiveStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sportsFlash\_active\_status** | *in* | *(bu)* |  |


### SportFlashFrequencyStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sportsFlash\_frequency\_status** | *in* | *u* |  |


### SportFlashFirstTimeUsageStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **firstTimeUsage** | *in* | *b* |  |


### EnableSportFlashAlertStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *in* | *u* |  |


### SelectSportsFlashTeamStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *in* | *u* |  |


### MoveSportsFlashTeamStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *in* | *u* |  |


### SportFlashAlert



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sportsFlash\_Alert** | *in* | *(uuuayayayu)* |  |


### CancelAlert



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sportsFlash\_cancel\_status** | *in* | *(uuu)* |  |


### PlayFlashAlertStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playFlash\_Alert\_Status** | *in* | *(uu)* |  |


### AbortFlashAlertStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **abortFlash\_Alert\_status** | *in* | *(buu)* |  |


### TurnOffAlertStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **turnOff\_Alert\_status** | *in* | *(uu)* |  |


### ReplayFlashAlertStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **replay\_Alert\_status** | *in* | *(uu)* |  |


### TWFlashActiveStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tWFlash\_active\_status** | *in* | *b* |  |


### TWFlashFrequencyStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tWFlash\_frequency\_status** | *in* | *u* |  |


### TWFirstTimeUsageStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **firstTimeUsage** | *in* | *b* |  |


### EnableTWReportAlertStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *in* | *u* |  |


### SelectTWCityStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *in* | *u* |  |


### TWCityNameCityID



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tW\_CityNameCityID** | *in* | *(aybuu)* |  |


### TWFlashAlert



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tWFlash\_Alert** | *in* | *(uuayu)* |  |


### FAVChannelsubscribed



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fAVChannel\_subscribed** | *in* | *(ubay)* |  |


### FavSportTeamCount



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **favSportTeamCount** | *in* | *y* |  |


### ChannelValidityStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **validityStatus** | *in* | *(uu)* |  |


### UnlockSession




### SubscriptionUpdated




### FlashAvailableStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **flashAvailable\_Status** | *in* | *(uuuuayayay)* |  |

