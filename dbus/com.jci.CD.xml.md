
# Dbus interface API

**com.jci.CD**


## Methods

### SourceChange\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Eject\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Play\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Pause\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Previous\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Next\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### SetRepeat\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **repeat** | *in* | *y* |  |
| **return\_value** | *out* | *i* |  |


### SetRandom\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **random** | *in* | *y* |  |
| **return\_value** | *out* | *i* |  |


### Scan\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### FastForward\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### FastRewind\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetCDReadyStatus\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cD\_Ready\_Status** | *out* | *y* |  |
| **return\_value** | *out* | *i* |  |


### GetCDStatus\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cD\_status** | *out* | *(yyyy)* |  |


### Get\_Availability\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cD\_RoutineTest\_Response** | *out* | *y* |  |
| **return\_value** | *out* | *i* |  |


### UserSelection\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **itemType** | *in* | *y* |  |
| **index** | *in* | *q* |  |
| **return\_value** | *out* | *(ysybb)* |  |


### UserSelection\_VR\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **itemType** | *in* | *y* |  |
| **index** | *in* | *q* |  |
| **return\_value** | *out* | *(ysybb)* |  |


### GetFolderContents\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **index** | *in* | *q* |  |
| **itemsCount** | *in* | *q* |  |
| **itemList** | *out* | *(a(qys))* |  |
| **listSize** | *out* | *n* |  |
| **totalItemsInFolder** | *out* | *n* |  |



## Signals

### Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cD\_status** | ** | *(yyyy)* |  |


### Ready\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ready\_status** | ** | *y* |  |


### Repeat\_Settings\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **repeat\_status** | ** | *y* |  |


### Random\_Settings\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **random\_status** | ** | *y* |  |


### Track\_Play\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **cD\_Track\_Play\_Status** | ** | *(qyyyyyy)* |  |


### Metadata\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **metadata\_Response** | ** | *(ssssss)* |  |


### SourceChange\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **change\_Response** | ** | *y* |  |


### RoutineTest\_Response



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **routineTest\_Response** | ** | *y* |  |


### Total\_Track\_Number



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **total\_track\_number** | ** | *q* |  |

