
# Dbus interface API

**com.jci.dab**


## Methods

### Get\_Dab\_Mode\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_Tuner\_Mode\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_Install\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_Channel\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_Signal\_Strength\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_TAU\_List\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Tuner\_Mode\_Change



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tuner\_mode** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### Scan\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **request** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### Compo\_Seek\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **request** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### Ens\_Seek\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **request** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### Direct\_Control\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **channel\_info** | *in* | *(ayqqy)* |  |
| **return\_value** | *out* | *i* |  |


### Update\_TAU\_List\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Link\_Setting\_Change\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **link\_setting** | *in* | *(ii)* |  |
| **return\_value** | *out* | *i* |  |


### Band\_Setting\_Change\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **band\_mode** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### TA\_Setting\_Change\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ta\_mode** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### Radio\_Text\_Setting\_Change\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **radio\_text\_mode** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### Get\_DAB\_DAB\_Setting\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_DAB\_FM\_Setting\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_Band\_Setting\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_TA\_Setting\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_Radio\_Text\_Setting\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Get\_TAU\_Connection\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Fav\_Seek\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fav\_seek\_dir** | *in* | *i* |  |
| **channel\_info** | *in* | *(ayqqy)* |  |
| **return\_value** | *out* | *i* |  |


### Factory\_Reset\_Setting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |



## Signals

### TAU\_Connection\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tau\_status** | ** | *i* |  |


### Signal\_Strength\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **signal\_strength** | ** | *i* |  |


### Link\_Setting\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **link\_setting** | ** | *(ii)* |  |


### Band\_Setting\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **band\_mode** | ** | *i* |  |


### TA\_Setting\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ta\_mode** | ** | *i* |  |


### Radio\_Text\_Setting\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **radio\_text\_mode** | ** | *i* |  |


### Full\_List\_Update\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | ** | *i* |  |


### Tuner\_Mode\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tuner\_mode** | ** | *i* |  |


### Dab\_Mode\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dab\_state** | ** | *(ii)* |  |


### TAU\_List\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **list\_status** | ** | *i* |  |


### Channel\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **channel\_info** | ** | *(ayqqy)* |  |


### Info\_Change\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **info\_change\_status** | ** | *(bbbbiay)* |  |


### Clear\_Label\_Field\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **clear\_label\_field** | ** | *(bbbb)* |  |


### Install\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **install\_status** | ** | *i* |  |


### Ens\_List\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | ** | *b* |  |


### Compo\_List\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **compo\_status** | ** | *(qb)* |  |


### New\_List\_Available



