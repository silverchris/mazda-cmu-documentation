
# Dbus interface API

**com.jci.bds**


## Methods

### SendCommand



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |
| **status** | *out* | *u* |  |


### TestMethod



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |



## Signals

### Signaltest\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |


### SignalReady\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalNotReady\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDeviceDeleteInProgress\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDeviceDeleted\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDeviceDeleteAllInProgress\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDeviceDeleteAll\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDeviceDisconnectedAll\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDeviceDisconnectionProgress\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDeviceInquiryResult\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDeviceNameStarted\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDeviceNameSet\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDeviceNameGet\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDeviceAccessibilityGet\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDevicePair\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDeviceServiceDiscovery\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDeviceWrittenAll\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDeviceAuthenticate\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalRemoteSupportedFeatures\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDeviceGetConnectedDevices\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDeviceLocalOobData\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDeviceExtendedSearchResult\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalServiceEnableStatus\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalServiceDisableStatus\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalConnected\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDisconnected\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalServiceFeatures\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalServiceConfiguration\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkAppChange\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkBatteryStatusChange\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkBiased\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkBrowseConnect\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkBrowseDisonnect\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkBrowseFolderChange\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkBrowseFolderContent\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkBrowseFolderContents\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkBrowseSearch\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkBrowseUidsChange\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkContentAddToNowPlaying\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkContentAttributes\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkContentPlay\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkMediaPosition\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkPanelOperation\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkPlaybackStatusChange\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkPlayerAddressedChange\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkPlayerBrowsedChange\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkPlayerItem\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkPlayerItems\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkPlayerItemsChange\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkPlayerNowContentChange\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkPlayerVolumeChange\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkStreamClosed\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkStreamConfigured\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkStreamLine\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkStreamMuted\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkStreamOpened\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkSupportedChanges\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkSupportedPlayerSetting\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkSystemStatusChange\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkTrackChange\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkTrackEnd\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkTrackMetaData\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalAudioSinkTrackStart\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalCallClientCallList\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalCallClientStatus\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalCallClientAudioConnect\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalCallClientAudioDisconnect\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalCallClientIndicator\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalCallClientOperator\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalCallClientSubscriber\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalCallClientMicVolumeChange\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalCallClientSpeakerVolumeChange\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalCallClientActivateVoiceDial\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalCallClientDeActivateVoiceDial\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalCallClientSiriSupportStatus\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalCallClientSiriEyesFreeMode\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalCallClientSiriDisableNoiseReduction\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalPhoneStatus\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalCallClientCmdError\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalCallClientScoCodecId\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalMessageClientConfigured\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalMessageClientFolderListing\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalMessageClientMessageDeleted\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalMessageClientMessageGotten\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalMessageClientMessageListing\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalMessageClientMessageNotification\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalMessageClientMessagePushed\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalMessageClientMessageSetStatus\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalNetworkClientConnected\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalNetworkClientDisconnected\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalPimClientImportStatus\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalFileServerInfoEvent\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalFileServerFileAcceptanceStatus\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalFileServerDataFileInProgressStatus\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalServiceLessAudioConnectStatus\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalServiceLessAudioDisconnectStatus\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalServiceLessAclConnectStatus\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalServiceLessAclDisconnectStatus\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalBTChipFailure\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |


### SignalDeviceAddressGet\_cb



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **data** | *in* | *(ay)* |  |

