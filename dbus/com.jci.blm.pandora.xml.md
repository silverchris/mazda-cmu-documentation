
# Dbus interface API

**com.jci.blm.pandora**


## Methods

### Connect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **statusId** | *out* | *i* |  |
| **sessionId** | *out* | *u* |  |
| **keepConnected** | *out* | *b* |  |


### Disconnect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **statusId** | *out* | *i* |  |


### Command



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **command** | *in* | *y* |  |
| **groupType** | *in* | *y* |  |
| **groupId** | *in* | *t* |  |
| **statusId** | *out* | *i* |  |


### Rate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **groupType** | *in* | *y* |  |
| **groupId** | *in* | *t* |  |
| **rating** | *in* | *y* |  |
| **statusId** | *out* | *i* |  |


### Bookmark



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **groupType** | *in* | *y* |  |
| **groupId** | *in* | *t* |  |
| **bookmarkType** | *in* | *y* |  |
| **statusId** | *out* | *i* |  |


### SetSort



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **sortType** | *in* | *y* |  |
| **statusId** | *out* | *i* |  |


### GetResource



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
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


### GetStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **statusId** | *out* | *i* |  |
| **connectStatus** | *out* | *y* |  |
| **linkStatus** | *out* | *y* |  |
| **playStatus** | *out* | *y* |  |
| **trackId** | *out* | *t* |  |
| **stationId** | *out* | *t* |  |
| **serviceSessionId** | *out* | *u* |  |
| **elapsedTime** | *out* | *u* |  |
| **buffering** | *out* | *u* |  |


### GetTrackAllInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **trackId** | *in* | *t* |  |
| **statusId** | *out* | *i* |  |
| **trackTitle** | *out* | *s* |  |
| **trackArtist** | *out* | *s* |  |
| **trackAlbum** | *out* | *s* |  |
| **trackGenre** | *out* | *s* |  |
| **trackDuration** | *out* | *u* |  |
| **artImageSize** | *out* | *u* |  |
| **artResourceId** | *out* | *u* |  |
| **currentStationId** | *out* | *t* |  |
| **trackRating** | *out* | *y* |  |
| **trackFlags** | *out* | *u* |  |


### GetStationAllInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **stationId** | *in* | *t* |  |
| **statusId** | *out* | *i* |  |
| **stationName** | *out* | *s* |  |
| **stationGenre** | *out* | *s* |  |
| **artImageSize** | *out* | *u* |  |
| **artResourceId** | *out* | *u* |  |
| **stationFlags** | *out* | *u* |  |


### GetStationListAllInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **startPosition** | *in* | *u* |  |
| **numberOfStations** | *in* | *u* |  |
| **statusId** | *out* | *i* |  |
| **startPos** | *out* | *u* |  |
| **currentSize** | *out* | *u* |  |
| **total** | *out* | *u* |  |
| **sortType** | *out* | *y* |  |
| **resStationIdsFlagsAndNames** | *out* | *(a(tus))* |  |


### GetGenreCategoryCount



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **count** | *out* | *y* |  |
| **statusId** | *out* | *i* |  |


### GetGenreCategoryNames



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **startPos** | *in* | *y* |  |
| **count** | *in* | *y* |  |
| **resultStartPos** | *out* | *y* |  |
| **genreCategoryNames** | *out* | *(as)* |  |
| **statusId** | *out* | *i* |  |


### GetAllGenreCategoryNames



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **genreCategoryNames** | *out* | *(as)* |  |
| **statusId** | *out* | *i* |  |


### GetGenreStationCount



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **categoryIndex** | *in* | *y* |  |
| **resultCategoryIndex** | *out* | *y* |  |
| **count** | *out* | *y* |  |
| **statusId** | *out* | *i* |  |


### GetGenreStationIdsNames



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **categoryIndex** | *in* | *y* |  |
| **startPos** | *in* | *y* |  |
| **count** | *in* | *y* |  |
| **resultCategoryIndex** | *out* | *y* |  |
| **resultStartPos** | *out* | *y* |  |
| **genreStationIdsNames** | *out* | *(a(ts))* |  |
| **statusId** | *out* | *i* |  |


### SelectGenreStation



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **categoryIndex** | *in* | *y* |  |
| **stationIndex** | *in* | *y* |  |
| **statusId** | *out* | *i* |  |


### GetListener



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **listenerId** | *out* | *s* |  |


### CreateStationFromCurrentTrack



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **statusId** | *out* | *i* |  |


### CreateStationFromCurrentArtist



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **statusId** | *out* | *i* |  |


### GetSessionId



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *out* | *u* |  |
| **statusId** | *out* | *i* |  |


### FavoritesAdd



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **stationId** | *in* | *t* |  |
| **statusId** | *out* | *i* |  |


### FavoritesRemove



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **stationId** | *in* | *t* |  |
| **statusId** | *out* | *i* |  |


### FavoritesGet



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *u* |  |
| **startPosition** | *in* | *y* |  |
| **numberOfFavorites** | *in* | *y* |  |
| **statusId** | *out* | *i* |  |
| **startPos** | *out* | *y* |  |
| **currentSize** | *out* | *y* |  |
| **total** | *out* | *y* |  |
| **favorites** | *out* | *(a(tus))* |  |



## Signals

### Connected



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |
| **keepConnected** | ** | *b* |  |


### Disconnected



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |
| **reasonId** | ** | *y* |  |


### UpdateStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |
| **linkStatus** | ** | *y* |  |
| **playStatus** | ** | *y* |  |
| **trackId** | ** | *t* |  |
| **stationId** | ** | *t* |  |
| **elapsedTime** | ** | *u* |  |
| **buffering** | ** | *u* |  |


### UpdateInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |
| **groupType** | ** | *y* |  |
| **groupId** | ** | *t* |  |
| **infoUpdated** | ** | *y* |  |
| **infoData** | ** | *t* |  |


### UpdateSort



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |
| **sortType** | ** | *y* |  |


### UpdateList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |
| **stationId** | ** | *t* |  |


### UpdateStationInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |
| **stationId** | ** | *t* |  |
| **stationStatus** | ** | *t* |  |
| **stationListCount** | ** | *u* |  |


### UpdateNoticeText



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |
| **noticeType** | ** | *y* |  |
| **noticeText** | ** | *s* |  |


### StationArtReady



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |
| **resourceId** | ** | *t* |  |
| **stationId** | ** | *t* |  |
| **resourcePath** | ** | *s* |  |


### GenreStationArtReady



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | ** | *u* |  |
| **resourceId** | ** | *t* |  |
| **categoryIndex** | ** | *y* |  |
| **stationIndex** | ** | *y* |  |
| **resourcePath** | ** | *s* |  |

