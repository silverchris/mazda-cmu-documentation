
# Dbus interface API

**com.jci.obs.stitcher.hmi**


## Methods

### ListSessions



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **statusId** | *out* | *i* |  |
| **sessions** | *out* | *(a(us))* |  |


### ListAttachedClients



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **statusId** | *out* | *i* |  |
| **clients** | *out* | *(as)* |  |


### AttachToSession



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **clientName** | *in* | *s* |  |
| **statusId** | *out* | *i* |  |


### DetachFromSession



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **clientName** | *in* | *s* |  |
| **statusId** | *out* | *i* |  |


### SetElapsedPolling



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **groupType** | *in* | *y* |  |
| **timeMs** | *in* | *u* |  |
| **statusId** | *out* | *i* |  |


### GetResource



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **groupType** | *in* | *y* |  |
| **groupId** | *in* | *t* |  |
| **resourceId** | *in* | *u* |  |
| **statusId** | *out* | *i* |  |
| **filePath** | *out* | *s* |  |


### ReleaseResource



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **resourceId** | *in* | *u* |  |
| **statusId** | *out* | *i* |  |


### StationGetListId



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **parentId** | *in* | *u* |  |
| **startPosition** | *in* | *u* |  |
| **numberOfStations** | *in* | *u* |  |
| **statusId** | *out* | *i* |  |
| **total** | *out* | *i* |  |
| **resStationId** | *out* | *(at)* |  |


### StationGetAllInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **stationId** | *in* | *t* |  |
| **statusId** | *out* | *i* |  |
| **stationAllInfo** | *out* | *(bssss(uu)uuu)* |  |


### TrackGetAllInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **trackId** | *in* | *t* |  |
| **statusId** | *out* | *i* |  |
| **trackAllInfo** | *out* | *(sssss(uu)uuuu(a(us))uutu)* |  |


### Bookmark



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **listType** | *in* | *y* |  |
| **type** | *in* | *y* |  |
| **id** | *in* | *t* |  |
| **name** | *in* | *s* |  |
| **statusId** | *out* | *i* |  |


### RequestPlaybackUpdateStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **status** | *out* | *i* |  |
| **playbackState** | *out* | *y* |  |
| **trackId** | *out* | *t* |  |
| **stationId** | *out* | *t* |  |
| **elapsedTime** | *out* | *u* |  |
| **buffering** | *out* | *u* |  |


### SelectFavourites



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **groupType** | *in* | *y* |  |
| **id** | *in* | *t* |  |
| **actions** | *in* | *(a(us))* |  |
| **status** | *out* | *i* |  |


### DeleteBookmark



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **listType** | *in* | *y* |  |
| **type** | *in* | *y* |  |
| **id** | *in* | *t* |  |
| **name** | *in* | *s* |  |
| **statusId** | *out* | *i* |  |


### StationGetListIdsAndNames



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **parentId** | *in* | *u* |  |
| **startPosition** | *in* | *u* |  |
| **numberOfStations** | *in* | *u* |  |
| **statusId** | *out* | *i* |  |
| **total** | *out* | *i* |  |
| **resStationIdsFlagsAndNames** | *out* | *(a(tus))* |  |



## Signals

### SessionDestroyed



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |
| **reasonId** | ** | *u* |  |


### PlaybackUpdateStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |
| **playbackState** | ** | *y* |  |
| **trackId** | ** | *t* |  |
| **stationId** | ** | *t* |  |
| **elapsedTime** | ** | *u* |  |
| **buffering** | ** | *u* |  |


### UpdateInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |
| **type** | ** | *y* |  |
| **id** | ** | *t* |  |
| **infoUpdated** | ** | *y* |  |
| **data** | ** | *t* |  |


### UpdateList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |
| **type** | ** | *y* |  |
| **id** | ** | *t* |  |


### UpdateNotificationText



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |
| **type** | ** | *y* |  |
| **text** | ** | *s* |  |
| **duration** | ** | *u* |  |


### BookmarkList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |
| **bookmarkListType** | ** | *u* |  |
| **bookmarkListData** | ** | *(as)* |  |

