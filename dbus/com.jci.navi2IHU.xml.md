
# Dbus interface API

**com.jci.navi2IHU**


## Methods

### ShowNavigation




### ClearStack




### FavoriteLongPress




### NaviButtonPress




### NaviFocusStatusUpdate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *in* | *i* |  |


### RequestShowNavigationDenied




### DisplayXMServices



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **screen** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### GetCurrentNaviState



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **naviState** | *out* | *i* |  |


### NavigateToAddress



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | *in* | *s* |  |
| **addressLine1** | *in* | *s* |  |
| **addressLine2** | *in* | *s* |  |
| **city** | *in* | *s* |  |
| **stateProvince** | *in* | *s* |  |
| **country** | *in* | *s* |  |
| **code** | *in* | *s* |  |
| **latitude** | *in* | *d* |  |
| **longitude** | *in* | *d* |  |


### SetLanguage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **language** | *in* | *i* |  |


### SetLanguageEx



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **display\_language** | *in* | *i* |  |
| **vr\_supported** | *in* | *b* |  |
| **vr\_language** | *in* | *i* |  |
| **tts\_language** | *in* | *i* |  |
| **keyboard\_language** | *in* | *i* |  |


### FactoryReset




### GetCurrentLocationInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **locinfoneeded** | *in* | *b* |  |


### GetVolumeScreenFocusStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **volumeScreenInFocus** | *out* | *b* |  |



## Signals

### NaviStateUpdate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **state** | ** | *i* |  |


### ReadyToShowNavi




### RequestShowNavigation




### NaviButtonPressed



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **buttonPressedID** | ** | *i* |  |


### DialPhoneNumber



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **phoneNumber** | ** | *s* |  |
| **name** | ** | *s* |  |


### NaviconDestinationRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | ** | *s* |  |
| **latitude** | ** | *d* |  |
| **longitude** | ** | *d* |  |


### LanguageChangeFinished



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | ** | *b* |  |
| **language** | ** | *i* |  |


### LanguageChangeFinishedEx



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | ** | *b* |  |
| **display\_language** | ** | *i* |  |
| **vr\_language** | ** | *i* |  |
| **tts\_language** | ** | *i* |  |
| **keyboard\_language** | ** | *i* |  |


### FactoryResetFinished



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | ** | *b* |  |


### CurrentLocationInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **latitude** | ** | *d* |  |
| **longitude** | ** | *d* |  |
| **altitude** | ** | *i* |  |
| **altitudeUnit** | ** | *i* |  |
| **isValidInfo** | ** | *b* |  |
| **heading** | ** | *d* |  |
| **isHeadingValid** | ** | *b* |  |
| **compassDirection** | ** | *y* |  |


### VolumeScreenFocusChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **volumeScreenInFocus** | ** | *b* |  |


### RequestScreenMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **screenMode** | ** | *i* |  |


### ReadyToShowNaviEx



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **screenMode** | ** | *i* |  |

