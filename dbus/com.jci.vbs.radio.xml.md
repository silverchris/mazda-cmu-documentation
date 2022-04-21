
# Dbus interface API

**com.jci.vbs.radio**


## Methods

### Tune\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tune** | *in* | *(yy)* |  |
| **return\_value** | *out* | *y* |  |


### Seek\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **seek** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### QuickSeek\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **quickSeek** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### Scan\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **scan** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### DirectControl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **directControl** | *in* | *(dqy)* |  |
| **return\_value** | *out* | *y* |  |


### Control1\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hARWrite** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### PTY\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pty** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### RDS\_AF\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **aF** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### RDS\_REG\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **rEG** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### HD\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hD** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### TA\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tA** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### SubTunerControl\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **subTunerReq** | *in* | *(yq)* |  |
| **return\_value** | *out* | *y* |  |


### HD\_ChannelUp\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hDChannelUp** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### HD\_ErrorRateDisplayMode\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hDErrorRateDisplayMode** | *in* | *y* |  |
| **hDTunerType** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### HD\_PageNumber\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hDPageNumber** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### HD\_DiagTestNum\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hDDiagTestNum** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### HD\_Parameter1\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hDParameter1** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### HD\_Parameter2\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hDParameter2** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### HD\_RadioErrorStatus\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hDRadioErrorStatus** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### Mute\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **mute** | *in* | *(yy)* |  |
| **return\_value** | *out* | *y* |  |


### Vol\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vol** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### AudioSettings\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **audioSettings** | *in* | *(yy)* |  |
| **return\_value** | *out* | *y* |  |


### ACUInitialization\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **aCUIn** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### ACUAudioPilot\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **audioPilot** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### ACUCenterPoint\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **centerPoint** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### StationListCreation\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **request** | *in* | *y* |  |
| **dest\_id** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### Text\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **textReq** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### HD\_SISStatus\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sISReq** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### HD\_PSD\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pSDRequest** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### HD\_ErrorStatus\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **errorStatusReq** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### AUTO\_M\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **autoM** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### XM\_DirectType\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **directType** | *in* | *y* |  |
| **stepCH** | *in* | *y* |  |
| **stepSID** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### XM\_RelativeTune\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **step** | *in* | *y* |  |
| **tuneDirection** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### XM\_Diag\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **diagRequest** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### XM\_ExpandedDiagMode\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **expDiagMode** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### XM\_Mute\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **muteReq** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### ElectricField\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **signalStrength** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### Test\_Mode\_Variation\_Page\_Antenna\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **testMode\_Variation\_Page\_Antenna** | *in* | *(yyyy)* |  |
| **return\_value** | *out* | *y* |  |


### AutoStore\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **autostore** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### GetConnStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### AUX\_GetConnStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### XM\_Config\_GetStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### GetDestinationType



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### GetRadioID



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### GetHDOnOffStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **returnHDOnOffStatus** | *out* | *y* |  |


### GetTAOnOffStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **returnTAOnOffStatus** | *out* | *y* |  |


### GetHARFreqSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **returnHARFreqSetting** | *out* | *y* |  |


### GetCurrentGenreSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **returnCurrentGenreSetting** | *out* | *y* |  |


### GetAlternateFreqOnOffStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **returnAlternateFreqOnOffStatus** | *out* | *y* |  |


### GetRegionLockOnOffStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **returnRegionLockOnOffStatus** | *out* | *y* |  |


### XM\_SendSignalInfoRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **xMSignalInfoReqType** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### HD\_GetTunerResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### GetTunerResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### XM\_GetRadioStatusResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### Get4ARegionInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_4A\_Region** | *out* | *y* |  |


### GetJapanRegionInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_Japan\_Region** | *out* | *y* |  |


### DAB\_Command\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dabCmdReq** | *in* | *(yyqq)* |  |
| **return\_value** | *out* | *y* |  |


### DAB\_Control\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dabCtrlReq** | *in* | *(yy)* |  |
| **return\_value** | *out* | *y* |  |


### DAB\_Get\_InfoStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dabInfoStatus** | *out* | *(bbb)* |  |


### DAB\_Get\_SignalStrength



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **signalStrength** | *out* | *y* |  |


### DAB\_Get\_ChStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **chStatus** | *out* | *(yayqqy)* |  |


### DAB\_Get\_ModeStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **modeStatus** | *out* | *(yy)* |  |


### DAB\_Get\_ListUpdateStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dabListUpdateStatus** | *out* | *y* |  |


### DAB\_DirectControl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **directCtrl** | *in* | *(ayqqy)* |  |
| **return\_value** | *out* | *y* |  |


### DAB\_Get\_Link\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dabLinkStatus** | *out* | *y* |  |


### DAB\_Get\_FMLink\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dabFMLinkStatus** | *out* | *y* |  |


### DAB\_Get\_BandSelect\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dabBandSelectStatus** | *out* | *y* |  |


### DAB\_Get\_TAUStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tauStatus** | *out* | *(yy)* |  |


### DAB\_InterruptNotification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **notify** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### XM\_SxiPowerSts



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sxiPowerSts** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### XM\_SxiBaudRate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sxiBaudRate** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### XM\_XmModuleResetReq



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **xmModuleResetReq** | *in* | *y* |  |
| **return\_value** | *out* | *y* |  |


### TauXmhSts\_getXmModulePowerSts



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **xmModulePowerSts** | *out* | *(yy)* |  |


### TauXmhSts\_getSxiCommandReq



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sxiCommandReq** | *out* | *(yy)* |  |



## Signals

### Tuner\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tunerStatus** | *in* | *(ayq)* |  |


### FrequencyLastKeep\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **lastKeepFrequency** | *in* | *y* |  |


### HARWrite\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **frequency** | *in* | *y* |  |


### PTY\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **recPTYResponse** | *in* | *y* |  |
| **selPTYResponse** | *in* | *y* |  |


### PTYChange\_Notification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **radioPTY** | *in* | *y* |  |


### AF\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **aFResponse** | *in* | *y* |  |


### REG\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **rEGResponse** | *in* | *y* |  |


### HD\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hDResponse** | *in* | *y* |  |


### HD\_Tuner\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hDTunerResponse** | *in* | *(yyyyayy)* |  |


### HD\_PSD\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hDPSDResponse** | *in* | *y* |  |


### TA\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tAResponse** | *in* | *y* |  |


### RDS\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **rDSResponse** | *in* | *y* |  |


### Metadata\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **metadata** | *in* | *y* |  |


### AudioSetting\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **audioSettings** | *in* | *(yy)* |  |


### ACU\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **aCUResponse** | *in* | *y* |  |


### StationList\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **stationListResp** | *in* | *y* |  |


### PresetInfo\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **presetInfoResponse** | *in* | *y* |  |


### Text\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **textResponse** | *in* | *(yay)* |  |


### HD\_SISStatus\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hDStatusResponse** | *in* | *(yyyyay)* |  |


### TAUSourceIndex\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sourceIndex** | *in* | *y* |  |
| **tauSourceStatus** | *in* | *y* |  |


### AMP\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **aMPStatus** | *in* | *(yyyyyyyyyyyyyyyy)* |  |


### TAControl\_Interrupt\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **interrupt** | *in* | *y* |  |


### TAUSoftwareVersion\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **softwareVersion** | *in* | *(uu)* |  |


### XM\_RefreshStatus\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **xMRefreshStatus** | *in* | *y* |  |


### XM\_RadioStatus\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **xMRadioStatus** | *in* | *(yyyyyy)* |  |


### XM\_Mute\_Status\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **xMMuteStatus** | *in* | *y* |  |


### AUX\_Status\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **aUXStatus** | *in* | *y* |  |


### TrackChange



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **trackChangeStatus** | *in* | *y* |  |


### StationChange



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **stationChangeStatus** | *in* | *d* |  |


### ModeChange



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **modeChangeStatus** | *in* | *(yay)* |  |


### OffOnNotification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **radioOnOffStatus** | *in* | *y* |  |


### DestinationCode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **radioDestinationCode** | *in* | *y* |  |


### DestinationType



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **radioDestinationType** | *in* | *y* |  |


### XM\_ConfigStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **radioXMConfigStat** | *in* | *y* |  |


### ConnectionStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **radioConnectionStatus** | *in* | *y* |  |


### RsesConnectStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **radioReesConnStat** | *in* | *y* |  |


### iTunes\_TaggingInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iTunesTaggingData** | *in* | *(yay)* |  |


### XM\_MAP\_Info



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **xmMapInfo** | *in* | *y* |  |


### XM\_Signal\_Info



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **xmSignalInfo** | *in* | *(ay)* |  |


### RDS\_HAR\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hARfrequency** | *in* | *y* |  |
| **hAROnStatus** | *in* | *y* |  |


### RDS\_TAInterrupt\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tAinterrupt** | *in* | *y* |  |


### TAU\_TestMode\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **testMode** | *in* | *(yyyyyyy)* |  |


### XM\_Title\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **xMTitleResponse** | *in* | *y* |  |


### XM\_Metadata\_Notification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **xmMetadataNotification** | *in* | *(yyyy)* |  |


### HD\_MetadataChange\_Notification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hDMetadataChangeNotification** | *in* | *(yyyyyyyyyyq)* |  |


### HD\_Tuner2\_Status\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hDRadioTuner2Status** | *in* | *(yq)* |  |


### Text\_Notification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **textNotification** | *in* | *y* |  |


### HD\_ID3\_XHDR\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hd\_ID3\_XHDR** | *in* | *(ay)* |  |


### XM\_ModuleData\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **xmModuleData** | *in* | *(yayyyyay)* |  |


### XM\_SerialNumber\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **xmSerialNumber** | *in* | *(uu)* |  |


### HD\_ErrorStatusResponse



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hdErrorStatus** | *in* | *(ayayayayayayayayayayyyy)* |  |


### HD\_RadioNumBlend\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hDRadioNumBlend** | *in* | *q* |  |


### SignalInfoChange\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **signalInfoChange** | *in* | *y* |  |


### XM\_MAP\_DuplicateChannelNotification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sid** | *in* | *y* |  |
| **channelNumber** | *in* | *y* |  |


### HD\_BER\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **berStatus** | *in* | *y* |  |


### HD\_BCTL\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **bctlStatus** | *in* | *y* |  |


### RDS\_AlarmInterrupt\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **alarmInterrupt** | *in* | *y* |  |


### New4ARegionInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **region** | *in* | *y* |  |


### NewJapanRegionInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **region** | *in* | *y* |  |


### DAB\_ChStatus\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dabChStatus** | *in* | *(yayqqy)* |  |


### DAB\_Mode\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dabModeStatus** | *in* | *(yy)* |  |


### DAB\_FMLinkSetting\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dabFMLink** | *in* | *y* |  |


### DAB\_LinkSetting\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dabLink** | *in* | *y* |  |


### DAB\_List\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **listStatus** | *in* | *y* |  |


### DAB\_BandSelectSetting\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dabBandSelecting** | *in* | *y* |  |


### DAB\_RadioText\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dabRadioText** | *in* | *y* |  |


### DAB\_SignalStrength\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dabSigStrgth** | *in* | *y* |  |


### DAB\_DiagMode\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dabDiagMode** | *in* | *y* |  |


### DAB\_EnsembleListMgmtInfo\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ensListMgmtInfo** | *in* | *(yy)* |  |


### DAB\_EnsembleInfoList\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ensInfoList** | *in* | *(yyqayay)* |  |


### DAB\_CompoListMgmtInfo\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **compoListMgmtInfo** | *in* | *(yqq)* |  |


### DAB\_CompoInfoList\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **compoInfoList** | *in* | *(yyqqyay)* |  |


### DAB\_Label\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **labelResp** | *in* | *(yyyay)* |  |


### DAB\_TAUConfig\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **configStatus** | *in* | *(yy)* |  |


### DAB\_Info\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dabInfoStatus** | *in* | *y* |  |


### DAB\_Diag\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **diagResp** | *in* | *(yquayyqqyyyqqyyy)* |  |


### DAB\_List\_Current\_State



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dabListCurrentState** | *in* | *y* |  |
| **dabListType** | *in* | *y* |  |


### DAB\_Text\_Info\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dabTextInfoStatus** | *in* | *y* |  |
| **dabContentType** | *in* | *y* |  |


### TauXmhSts\_XmModulePowerSts



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **xmModulePowerSts** | *in* | *(yy)* |  |


### TauXmhSts\_SxiCommandReq



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sxiCommandReq** | *in* | *(yy)* |  |

