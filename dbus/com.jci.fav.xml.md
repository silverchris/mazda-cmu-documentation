
# Dbus interface API

**com.jci.fav**


## Methods

### GetFavoriteMax



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *i* |  |
| **category** | *in* | *u* |  |
| **deviceId** | *in* | *u* |  |
| **return\_requestId** | *out* | *i* |  |
| **return\_category** | *out* | *u* |  |
| **return\_number\_fav** | *out* | *i* |  |
| **return\_max\_fav** | *out* | *i* |  |
| **return\_max\_reached** | *out* | *b* |  |
| **return\_status** | *out* | *u* |  |


### AddFavoriteRadio



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *i* |  |
| **displayText** | *in* | *s* |  |
| **replaceFavId** | *in* | *i* |  |
| **stationType** | *in* | *u* |  |
| **frequency** | *in* | *d* |  |
| **stationName** | *in* | *s* |  |
| **piCode** | *in* | *q* |  |
| **hdSPS** | *in* | *u* |  |
| **xM\_step** | *in* | *y* |  |
| **xM\_category** | *in* | *y* |  |
| **xM\_channel** | *in* | *y* |  |
| **xM\_SID** | *in* | *y* |  |
| **relayName** | *in* | *s* |  |
| **fav\_dab\_data** | *in* | *(sqqys)* |  |
| **return\_requestId** | *out* | *i* |  |
| **return\_status** | *out* | *u* |  |
| **return\_add\_favId** | *out* | *i* |  |
| **return\_max\_reached** | *out* | *b* |  |


### DeleteFavorite



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *i* |  |
| **category** | *in* | *u* |  |
| **favId** | *in* | *i* |  |
| **deviceId** | *in* | *u* |  |
| **return\_requestId** | *out* | *i* |  |
| **return\_status** | *out* | *u* |  |


### MoveFavorite



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *i* |  |
| **category** | *in* | *u* |  |
| **favId** | *in* | *i* |  |
| **deviceId** | *in* | *u* |  |
| **oldIndex** | *in* | *i* |  |
| **newIndex** | *in* | *i* |  |
| **return\_requestId** | *out* | *i* |  |
| **return\_status** | *out* | *u* |  |


### RenameFavorite



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *i* |  |
| **category** | *in* | *u* |  |
| **favId** | *in* | *i* |  |
| **deviceId** | *in* | *u* |  |
| **displayText** | *in* | *s* |  |
| **return\_requestId** | *out* | *i* |  |
| **return\_status** | *out* | *u* |  |


### GetFavoriteRadio



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *i* |  |
| **favId** | *in* | *i* |  |
| **return\_requestId** | *out* | *i* |  |
| **return\_favId** | *out* | *i* |  |
| **return\_stationType** | *out* | *u* |  |
| **return\_frequency** | *out* | *d* |  |
| **return\_stationName** | *out* | *s* |  |
| **return\_piCode** | *out* | *q* |  |
| **return\_hdSPS** | *out* | *u* |  |
| **return\_XM\_step** | *out* | *y* |  |
| **return\_XM\_category** | *out* | *y* |  |
| **return\_XM\_channel** | *out* | *y* |  |
| **return\_XM\_SID** | *out* | *y* |  |
| **return\_status** | *out* | *u* |  |
| **fav\_dab\_data** | *out* | *(sqqys)* |  |


### GetFavoriteList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *i* |  |
| **category** | *in* | *u* |  |
| **deviceId** | *in* | *u* |  |
| **startIndex** | *in* | *i* |  |
| **maxItems** | *in* | *i* |  |
| **return\_requestId** | *out* | *i* |  |
| **return\_category** | *out* | *u* |  |
| **return\_startIndex** | *out* | *i* |  |
| **return\_numItems** | *out* | *i* |  |
| **return\_totItems** | *out* | *i* |  |
| **favList** | *out* | *(a(ususbss))* |  |


### RenameTuneMixFavorite



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *i* |  |
| **tuneMixID** | *in* | *u* |  |
| **displayText** | *in* | *s* |  |
| **return\_requestId** | *out* | *i* |  |
| **return\_status** | *out* | *u* |  |


### AddFavoriteComm



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *i* |  |
| **displayText** | *in* | *s* |  |
| **replaceFavId** | *in* | *i* |  |
| **deviceId** | *in* | *u* |  |
| **contactId** | *in* | *u* |  |
| **contactType** | *in* | *u* |  |
| **contactName** | *in* | *s* |  |
| **phoneNumber** | *in* | *s* |  |
| **return\_requestId** | *out* | *i* |  |
| **return\_status** | *out* | *u* |  |
| **return\_add\_favId** | *out* | *i* |  |
| **return\_max\_reached** | *out* | *b* |  |


### GetFavoriteContactDetail



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *i* |  |
| **favId** | *in* | *i* |  |
| **deviceId** | *in* | *u* |  |
| **return\_requestId** | *out* | *i* |  |
| **return\_favId** | *out* | *i* |  |
| **return\_status** | *out* | *u* |  |
| **return\_displayName** | *out* | *s* |  |
| **return\_companyName** | *out* | *s* |  |
| **return\_image** | *out* | *s* |  |
| **favCommNum** | *out* | *(a(us))* |  |
| **favCommAddr** | *out* | *(usssss)* |  |


### GetFavoriteComm



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *i* |  |
| **favId** | *in* | *i* |  |
| **deviceId** | *in* | *u* |  |
| **return\_requestId** | *out* | *i* |  |
| **return\_favId** | *out* | *i* |  |
| **return\_contactId** | *out* | *u* |  |
| **return\_contactType** | *out* | *u* |  |
| **return\_displayName** | *out* | *s* |  |
| **return\_phoneNumber** | *out* | *s* |  |
| **return\_status** | *out* | *u* |  |


### RadioFavoriteSeek



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *i* |  |
| **radioType** | *in* | *u* |  |
| **frequency** | *in* | *d* |  |
| **hdSPS** | *in* | *u* |  |
| **xM\_channel** | *in* | *y* |  |
| **button** | *in* | *i* |  |
| **fav\_dab\_data** | *in* | *(sqqys)* |  |
| **return\_requestId** | *out* | *i* |  |
| **return\_favId** | *out* | *i* |  |
| **return\_stationType** | *out* | *u* |  |
| **return\_frequency** | *out* | *d* |  |
| **return\_stationName** | *out* | *s* |  |
| **return\_piCode** | *out* | *q* |  |
| **return\_hdSPS** | *out* | *u* |  |
| **return\_XM\_step** | *out* | *y* |  |
| **return\_XM\_category** | *out* | *y* |  |
| **return\_XM\_channel** | *out* | *y* |  |
| **return\_XM\_SID** | *out* | *y* |  |
| **return\_status** | *out* | *u* |  |
| **fav\_dab\_return** | *out* | *(sqqy)* |  |


### ReplaceFavoriteXMChannel



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *i* |  |
| **stationName** | *in* | *s* |  |
| **xM\_channel** | *in* | *y* |  |
| **xM\_SID** | *in* | *y* |  |
| **return\_requestId** | *out* | *i* |  |
| **return\_status** | *out* | *u* |  |


### ReplaceFavoriteSXMChannel



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *i* |  |
| **stationName** | *in* | *s* |  |
| **xM\_channel** | *in* | *q* |  |
| **xM\_SID** | *in* | *u* |  |
| **return\_requestId** | *out* | *i* |  |
| **return\_channelId** | *out* | *q* |  |
| **return\_status** | *out* | *u* |  |


### UpdateFromTunerStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tuner\_status** | *in* | *(yyyyybay)* |  |
| **return\_status** | *out* | *u* |  |


### CurrentTunedChannelInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **radioType** | *in* | *u* |  |
| **tuneStatus** | *in* | *b* |  |
| **frequency** | *in* | *d* |  |
| **piCode** | *in* | *q* |  |
| **hdSPS** | *in* | *u* |  |
| **xM\_channel** | *in* | *y* |  |
| **fav\_dab\_data** | *in* | *(sqqy)* |  |


### RadioFastFavoriteSeek



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *i* |  |
| **button** | *in* | *i* |  |
| **fimGroupAtKeyPressed** | *in* | *u* |  |
| **return\_requestId** | *out* | *i* |  |
| **return\_status** | *out* | *u* |  |


### GetFavoriteXMADAudio



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestId** | *in* | *i* |  |
| **return\_requestId** | *out* | *i* |  |
| **return\_numItems** | *out* | *i* |  |
| **channelIDArray** | *out* | *(au)* |  |


### DelXMADChannelFavID



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **xmChannelId** | *in* | *u* |  |
| **return\_favId** | *out* | *u* |  |
| **return\_status** | *out* | *u* |  |


### ShowSXMSFav



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestID** | *in* | *u* |  |
| **sXMSFavStatus** | *in* | *u* |  |
| **ret\_requestID** | *out* | *u* |  |
| **return\_status** | *out* | *u* |  |


### SmartFavoritesImpactList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **chId\_Arry** | *in* | *(au)* |  |
| **return\_status** | *out* | *u* |  |


### GetXMChipType



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestID** | *in* | *u* |  |
| **ret\_requestID** | *out* | *u* |  |
| **return\_status** | *out* | *u* |  |


### GetTunemixactiveStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **requestID** | *in* | *u* |  |
| **ret\_requestID** | *out* | *u* |  |
| **return\_status** | *out* | *u* |  |



## Signals

### SeekStatusResp



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **seekStatus** | ** | *u* |  |
| **fimGroupAtKeyPressed** | ** | *u* |  |


### FavRadioChangeEvent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_favId** | ** | *i* |  |
| **return\_stationType** | ** | *u* |  |
| **return\_frequency** | ** | *d* |  |
| **return\_stationName** | ** | *s* |  |
| **return\_piCode** | ** | *q* |  |
| **return\_hdSPS** | ** | *u* |  |
| **return\_XM\_step** | ** | *y* |  |
| **return\_XM\_category** | ** | *y* |  |
| **return\_XM\_channel** | ** | *y* |  |
| **return\_XM\_SID** | ** | *y* |  |
| **return\_status** | ** | *u* |  |
| **fav\_dab\_data** | ** | *(sqqys)* |  |


### SendActiveFavIdEvent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **favId** | ** | *u* |  |
| **favPlayStatus** | ** | *b* |  |


### SendFavInitStatusEvent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **isActive** | ** | *b* |  |


### XMADFavAddedEvent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **xM\_channel** | ** | *u* |  |


### XMADFavDeletedEvent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **xM\_channel** | ** | *u* |  |


### SetSmartFavoritesImpactList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **chId\_Arry** | ** | *(au)* |  |


### XMChiptype



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **isX65HAinstalled** | ** | *u* |  |


### TuneMixActiveStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **istunemixactive** | ** | *b* |  |

