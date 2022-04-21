
# Dbus interface API

**com.jci.radio**


## Methods

### Mode\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **mode** | *in* | *i* |  |
| **band** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### Japan\_Region\_specific\_Tau\_type\_info\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Tune\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **direction** | *in* | *i* |  |
| **steps** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### Scan\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **request** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### Seek\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **request** | *in* | *i* |  |
| **direction** | *in* | *i* |  |
| **genreseek\_screen** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### ForceSeek\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **forceSeek\_Type** | *in* | *i* |  |
| **direction** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### Tune\_Direct\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tune\_direct** | *in* | *(dqi)* |  |
| **return\_value** | *out* | *i* |  |


### Favorite\_Mode\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **mode** | *in* | *i* |  |
| **band** | *in* | *i* |  |
| **tune\_direct** | *in* | *(dqi)* |  |
| **return\_value** | *out* | *i* |  |


### Station\_List\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **list\_req\_type** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### Auto\_M\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **auto\_M\_req\_type** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### Area\_Preset\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_HDsetting\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_TAsetting\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_AFsetting\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_RegionLockSetting\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_HARfreqSetting\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_CurrentGenre\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Pty\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pty\_req\_type** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### Setting\_Change\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setting\_type** | *in* | *i* |  |
| **setting\_mode** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### HD\_ChUp\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hd\_ChUp\_req** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### HAR\_Freq\_change



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **frequency** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### Cancel\_Traffic\_alert



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_TAU\_Connection\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Fav\_Seek\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fav\_seek\_dir** | *in* | *i* |  |
| **current\_freq** | *in* | *d* |  |
| **return\_value** | *out* | *i* |  |


### Get\_Tuner\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_HDTuner\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_Mode\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Region\_specific\_info\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_Bose\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *y* |  |


### Factory\_Reset\_Setting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |



## Signals

### Bose\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **boseStatus** | ** | *y* |  |


### TAU\_Connection\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tau\_status** | ** | *i* |  |


### Tuner\_mode\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tuner\_mode\_status** | ** | *(ii)* |  |


### Tuner\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tuner\_status** | ** | *(iidayiayay)* |  |


### Station\_list\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **list\_status** | ** | *i* |  |


### Auto\_M\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **auto\_m\_status** | ** | *i* |  |


### Area\_Preset\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **area\_preset\_status** | ** | *i* |  |


### HD\_setting\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hd\_status** | ** | *i* |  |


### TA\_setting\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ta\_status** | ** | *i* |  |


### HAR\_setting\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **har\_status** | ** | *i* |  |


### AF\_setting\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **af\_status** | ** | *i* |  |


### RegionLock\_setting\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **region\_lock\_status** | ** | *i* |  |


### Current\_genre\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **current\_genre\_status** | ** | *i* |  |


### Metadata\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **metadata\_status** | ** | *i* |  |


### Setting\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setting\_mode\_status** | ** | *i* |  |
| **setting\_type** | ** | *i* |  |


### Pty\_response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pty\_received** | ** | *i* |  |
| **pty\_requested** | ** | *i* |  |


### HD\_tuner\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hd\_tuner\_status** | ** | *(iiibbab)* |  |


### HAR\_status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **har\_transmission\_status** | ** | *(ii)* |  |


### Traffic\_alert



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **traffic\_alert** | ** | *i* |  |


### Metadata\_Artisticinfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **artistic\_info** | ** | *i* |  |


### Metadata\_change\_notification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **metadata\_change** | ** | *(bbbbbbb)* |  |


### Japan\_Region\_specific\_notification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **japan\_Region\_info** | ** | *i* |  |


### Region\_specific\_notification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **region\_info** | ** | *i* |  |

