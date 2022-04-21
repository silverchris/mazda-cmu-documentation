
# Dbus interface API

**com.jci.usbm**


## Methods

### GetAlbumArt



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **album\_art** | *in* | *(uu)* |  |
| **album\_art\_reply** | *out* | *(suu)* |  |


### SelectDevice



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **select\_device** | *in* | *(u)* |  |
| **select\_device\_reply** | *out* | *(uu)* |  |


### PlaybackCommand



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playback\_command** | *in* | *(uuu)* |  |
| **result** | *out* | *i* |  |


### PlayResume



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **play\_resume** | *in* | *(uu)* |  |
| **play\_resume\_reply** | *out* | *((iuuui)uusu)* |  |


### PlayContext



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **play\_context** | *in* | *(u(iuuui)su)* |  |
| **play\_context\_reply** | *out* | *(uuu)* |  |


### SetRepeatMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dev\_id** | *in* | *u* |  |
| **repeat\_mode** | *in* | *u* |  |
| **result** | *out* | *i* |  |


### SetShuffleMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dev\_id** | *in* | *u* |  |
| **shuffle\_mode** | *in* | *u* |  |
| **result** | *out* | *i* |  |


### GetDeviceList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **device\_list** | *out* | *(a(uusuubbbuuss))* |  |
| **result** | *out* | *i* |  |


### GetCurrentObjectInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **obj\_info** | *out* | *(ussss)* |  |
| **result** | *out* | *i* |  |


### StartSeeking



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dev\_id** | *in* | *u* |  |
| **sec\_step** | *in* | *u* |  |
| **seek\_dir** | *in* | *u* |  |
| **result** | *out* | *i* |  |


### PlaybackJumpToPosition



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dev\_id** | *in* | *u* |  |
| **new\_pb\_position** | *in* | *u* |  |
| **result** | *out* | *i* |  |


### MoreLikeThis



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **device\_id** | *in* | *u* |  |
| **more\_like\_this\_reply** | *out* | *(su)* |  |


### SetLanguage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sys\_lang** | *in* | *i* |  |
| **result** | *out* | *i* |  |



## Signals

### DeviceConnected



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dev\_inf** | ** | *(uusuubbbuuss)* |  |


### DeviceDisconnected



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dev\_id** | ** | *u* |  |
| **reason** | ** | *i* |  |


### UpdateDeviceInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dev\_inf** | ** | *(uusuubbbuuss)* |  |


### PlayComplete



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **reason** | ** | *u* |  |


### DeviceSelected



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dev\_id** | ** | *u* |  |
| **err\_type** | ** | *i* |  |


### MetadataBrowsingPossible



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **filenum\_updated\_dev\_info** | *in* | *(uusubb)* |  |


### MltPossible



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **updated\_dev\_info** | *in* | *(uusu)* |  |


### PlaybackPossible



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **filenum\_updated\_dev\_info** | *in* | *(uusubb)* |  |


### FolderBrowsingPossible



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **updated\_dev\_info** | *in* | *(uusu)* |  |


### DeviceError



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **device\_error** | ** | *(uu)* |  |


### PlaybackInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playback\_info** | ** | *(uuussu(ussss)uuub)* |  |


### DbUpdate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dbupdate** | ** | *(uuu)* |  |


### AlbumArtReady



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **album\_art\_ready** | ** | *(u)* |  |


### CurrentObjectInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **obj\_info** | ** | *(ussss)* |  |


### PlaybackInterrupted



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **playback\_interrupted\_info** | ** | *((uuussu(ussss)uuub)u)* |  |

