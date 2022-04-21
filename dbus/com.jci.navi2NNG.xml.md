
# Dbus interface API

**com.jci.navi2NNG**


## Methods

### GetVDELang



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **language** | *out* | *s* |  |


### GetTTSLang



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **language** | *out* | *i* |  |


### GetLanguage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **language** | *out* | *i* |  |


### GetVIN



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vIN** | *out* | *s* |  |


### GetRegionAndBranding



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **region** | *out* | *s* |  |
| **branding** | *out* | *s* |  |


### GetSpeedLimitSign



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **speedLimitSignMask** | *out* | *i* |  |


### GetSpeedLimitCaution



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **speedLimitCaution** | *out* | *i* |  |


### GetSpeedLimitCautionSpeed



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **speedLimitCautionSpeed** | *out* | *i* |  |


### GetTemperatureUnit



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tempUnit** | *out* | *i* |  |


### GetDayNightMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **mode** | *out* | *i* |  |


### GetTimeFormat



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **format** | *out* | *i* |  |


### GetLengthUnit



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **unit** | *out* | *i* |  |


### GetPhoneConnectionStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **phoneStatus** | *out* | *i* |  |


### GetFuelType



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fuelType** | *out* | *i* |  |


### GetNetworkConnectionStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **networkConnectionStatus** | *out* | *i* |  |


### GetAvailableLayouts



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **layouts** | *out* | *(ia(i))* |  |


### GetKeyboardLayout



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **keyboardLayout** | *out* | *i* |  |


### GetRecentKeyboardNumber



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **numberOfRecentKeyboards** | *out* | *i* |  |


### GetSpeedRestriction



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **speedRestriction** | *out* | *i* |  |


### GetLocalizedRecentText



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **recentText** | *out* | *s* |  |


### GetShowSpeedingSettingMenu



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **showSpeedingSettingMenu** | *out* | *i* |  |


### GetHubType



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hubType** | *out* | *i* |  |


### GetVolumeRequestEnabled



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestEnabled** | *out* | *i* |  |


### GetNavigationVolume



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **volume** | *out* | *i* |  |


### DialPhoneNumber



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **phoneNumber** | *in* | *s* |  |
| **name** | *in* | *s* |  |


### GetTimeMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **mode** | *out* | *i* |  |
| **timeStamp** | *out* | *t* |  |
| **displayedTime** | *out* | *(nyyyyy)* |  |


### GetDRUnitStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ismounted** | *out* | *b* |  |
| **nodename** | *out* | *s* |  |



## Signals

### ShutdownRequest




### FactoryReset




### ShowNavigation




### ShowNaviScreen



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **screenId** | ** | *i* |  |


### RequestShowNavigationDenied




### ClearStack




### FavoriteLongPress




### NaviButtonPress




### GuiFocusStatusUpdate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | ** | *i* |  |


### AudioDone



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **callbackId** | ** | *i* |  |
| **result** | ** | *i* |  |


### SetNavigationVolume



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **volume** | ** | *i* |  |


### VREvent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **eventId** | ** | *s* |  |


### SelectedListItem



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **seletedItem** | ** | *i* |  |


### NavigateToPOI



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **poiCategoryName** | ** | *(ia(s))* |  |


### AddWaypointPOI



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **poiCategoryName** | ** | *(ia(s))* |  |


### JpjIntermediateHypothesis



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **jpjHypothesis** | ** | *(uuuuuu)* |  |


### JpjVDEHypothesisList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **jpjHypothesisList** | ** | *(ia(uuuuuu))* |  |


### VDEHypothesisList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vDEList** | ** | *(ia(uuuu))* |  |


### SimpleHypothesisList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **idList** | ** | *(ia(u))* |  |


### UniVDEHypothesisList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **uniVDEHypothesisList** | ** | *(ia(s))* |  |


### UniSimpleHypothesisList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **uniSimpleHypothesisList** | ** | *(ia(s))* |  |


### ModeChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **modality** | ** | *i* |  |


### RequestGuidanceInfo




### NavigateToAddress



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | ** | *s* |  |
| **countryName** | ** | *s* |  |
| **stateName** | ** | *s* |  |
| **cityName** | ** | *s* |  |
| **streetName** | ** | *s* |  |
| **zipCode** | ** | *s* |  |
| **latitude** | ** | *d* |  |
| **longitude** | ** | *d* |  |


### DeleteFavorite



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iD** | ** | *u* |  |


### DeleteAllFavorites




### NavigateToFavorite



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iD** | ** | *u* |  |


### RenameFavorite



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iD** | ** | *u* |  |
| **name** | ** | *s* |  |


### SetHome




### UnsetHome




### SwapFavorites



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iD1** | ** | *u* |  |
| **iD2** | ** | *u* |  |


### MoveFavorite



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iD1** | ** | *u* |  |
| **iD2** | ** | *u* |  |


### AddCurrentPositionToFavorites




### ReplaceFavoriteWithCurrentPosition



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iD** | ** | *u* |  |


### AddCurrentDestinationToFavorites




### ReplaceFavoriteWithCurrentDestination



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iD** | ** | *u* |  |


### AddFavorite



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | ** | *s* |  |
| **countryName** | ** | *s* |  |
| **stateName** | ** | *s* |  |
| **cityName** | ** | *s* |  |
| **streetName** | ** | *s* |  |
| **zipCode** | ** | *s* |  |
| **latitude** | ** | *d* |  |
| **longitude** | ** | *d* |  |


### ReplaceFavoriteWithAddress



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iD** | ** | *u* |  |
| **name** | ** | *s* |  |
| **countryName** | ** | *s* |  |
| **stateName** | ** | *s* |  |
| **cityName** | ** | *s* |  |
| **streetName** | ** | *s* |  |
| **zipCode** | ** | *s* |  |
| **latitude** | ** | *d* |  |
| **longitude** | ** | *d* |  |

