
# Dbus interface API

**com.jci.navi2IHU.NaviFavorites**


## Methods

### AddFavorite



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | *in* | *s* |  |
| **countryName** | *in* | *s* |  |
| **stateName** | *in* | *s* |  |
| **cityName** | *in* | *s* |  |
| **streetName** | *in* | *s* |  |
| **zipCode** | *in* | *s* |  |
| **latitude** | *in* | *d* |  |
| **longitude** | *in* | *d* |  |


### ReplaceFavoriteWithAddress



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iD** | *in* | *u* |  |
| **name** | *in* | *s* |  |
| **countryName** | *in* | *s* |  |
| **stateName** | *in* | *s* |  |
| **cityName** | *in* | *s* |  |
| **streetName** | *in* | *s* |  |
| **zipCode** | *in* | *s* |  |
| **latitude** | *in* | *d* |  |
| **longitude** | *in* | *d* |  |


### DeleteFavorite



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iD** | *in* | *u* |  |


### DeleteAllFavorites




### NavigateToFavorite



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iD** | *in* | *u* |  |


### SetHome




### UnsetHome




### RenameFavorite



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iD** | *in* | *u* |  |
| **name** | *in* | *s* |  |


### MoveFavorite



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iD1** | *in* | *u* |  |
| **iD2** | *in* | *u* |  |


### SwapFavorite



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iD1** | *in* | *u* |  |
| **iD2** | *in* | *u* |  |


### AddCurrentPositionToFavorites




### ReplaceFavoriteWithCurrentPosition



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iD** | *in* | *u* |  |


### AddCurrentDestinationToFavorites




### ReplaceFavoriteWithCurrentDestination



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **iD** | *in* | *u* |  |


### NavigatedRouteExists



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **result** | *out* | *i* |  |


### GetFavoriteList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **startIndex** | *in* | *i* |  |
| **maxItems** | *in* | *i* |  |
| **favoriteList** | *out* | *(ia(us))* |  |


### GetFavoritesCount



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **count** | *out* | *i* |  |



## Signals

### FavoriteButtonPressed




### FavoriteOperationResult



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **result** | ** | *i* |  |

