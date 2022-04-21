
# Dbus interface API

**com.jci.settings**


## Methods

### Connect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **client\_name** | *in* | *s* |  |
| **status** | *out* | *i* |  |


### Disconnect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **client\_name** | *in* | *s* |  |
| **status** | *out* | *i* |  |


### Get\_Settings\_U8



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **key\_path** | *in* | *s* |  |
| **key\_group** | *in* | *s* |  |
| **key\_name** | *in* | *s* |  |
| **user\_fun** | *in* | *u* |  |
| **key\_actions** | *in* | *u* |  |
| **val** | *out* | *y* |  |
| **user\_fun\_out** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### Set\_Settings\_U8



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **key\_path** | *in* | *s* |  |
| **key\_group** | *in* | *s* |  |
| **key\_name** | *in* | *s* |  |
| **val** | *in* | *y* |  |
| **user\_fun** | *in* | *u* |  |
| **key\_actions** | *in* | *u* |  |
| **val\_ret** | *out* | *y* |  |
| **user\_fun\_out** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### OnChange\_Settings\_U8



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **client\_name** | *in* | *s* |  |
| **key\_path** | *in* | *s* |  |
| **key\_group** | *in* | *s* |  |
| **key\_name** | *in* | *s* |  |
| **user\_signalcb\_fun** | *in* | *u* |  |
| **user\_fun** | *in* | *u* |  |
| **key\_actions** | *in* | *u* |  |
| **user\_fun\_out** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### Reset\_Settings\_U8



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **key\_path** | *in* | *s* |  |
| **key\_group** | *in* | *s* |  |
| **key\_name** | *in* | *s* |  |
| **user\_fun** | *in* | *u* |  |
| **key\_actions** | *in* | *u* |  |
| **user\_fun\_out** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### Get\_Settings\_S16



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **key\_path** | *in* | *s* |  |
| **key\_group** | *in* | *s* |  |
| **key\_name** | *in* | *s* |  |
| **user\_fun** | *in* | *u* |  |
| **key\_actions** | *in* | *u* |  |
| **val** | *out* | *n* |  |
| **user\_fun\_out** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### Set\_Settings\_S16



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **key\_path** | *in* | *s* |  |
| **key\_group** | *in* | *s* |  |
| **key\_name** | *in* | *s* |  |
| **val** | *in* | *n* |  |
| **user\_fun** | *in* | *u* |  |
| **key\_actions** | *in* | *u* |  |
| **val\_ret** | *out* | *n* |  |
| **user\_fun\_out** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### OnChange\_Settings\_S16



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **client\_name** | *in* | *s* |  |
| **key\_path** | *in* | *s* |  |
| **key\_group** | *in* | *s* |  |
| **key\_name** | *in* | *s* |  |
| **user\_signalcb\_fun** | *in* | *u* |  |
| **user\_fun** | *in* | *u* |  |
| **key\_actions** | *in* | *u* |  |
| **user\_fun\_out** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### Reset\_Settings\_S16



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **key\_path** | *in* | *s* |  |
| **key\_group** | *in* | *s* |  |
| **key\_name** | *in* | *s* |  |
| **user\_fun** | *in* | *u* |  |
| **key\_actions** | *in* | *u* |  |
| **user\_fun\_out** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### Get\_Settings\_U32



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **key\_path** | *in* | *s* |  |
| **key\_group** | *in* | *s* |  |
| **key\_name** | *in* | *s* |  |
| **user\_fun** | *in* | *u* |  |
| **key\_actions** | *in* | *u* |  |
| **val** | *out* | *u* |  |
| **user\_fun\_out** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### Set\_Settings\_U32



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **key\_path** | *in* | *s* |  |
| **key\_group** | *in* | *s* |  |
| **key\_name** | *in* | *s* |  |
| **val** | *in* | *u* |  |
| **user\_fun** | *in* | *u* |  |
| **key\_actions** | *in* | *u* |  |
| **val\_ret** | *out* | *u* |  |
| **user\_fun\_out** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### OnChange\_Settings\_U32



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **client\_name** | *in* | *s* |  |
| **key\_path** | *in* | *s* |  |
| **key\_group** | *in* | *s* |  |
| **key\_name** | *in* | *s* |  |
| **user\_signalcb\_fun** | *in* | *u* |  |
| **user\_fun** | *in* | *u* |  |
| **key\_actions** | *in* | *u* |  |
| **user\_fun\_out** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### Reset\_Settings\_U32



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **key\_path** | *in* | *s* |  |
| **key\_group** | *in* | *s* |  |
| **key\_name** | *in* | *s* |  |
| **user\_fun** | *in* | *u* |  |
| **key\_actions** | *in* | *u* |  |
| **user\_fun\_out** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### Get\_Settings\_BLM\_Settings\_pChar



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **key\_path** | *in* | *s* |  |
| **key\_group** | *in* | *s* |  |
| **key\_name** | *in* | *s* |  |
| **user\_fun** | *in* | *u* |  |
| **key\_actions** | *in* | *u* |  |
| **val** | *out* | *s* |  |
| **user\_fun\_out** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### Set\_Settings\_BLM\_Settings\_pChar



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **key\_path** | *in* | *s* |  |
| **key\_group** | *in* | *s* |  |
| **key\_name** | *in* | *s* |  |
| **val** | *in* | *s* |  |
| **user\_fun** | *in* | *u* |  |
| **key\_actions** | *in* | *u* |  |
| **val\_ret** | *out* | *s* |  |
| **user\_fun\_out** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### OnChange\_Settings\_BLM\_Settings\_pChar



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **client\_name** | *in* | *s* |  |
| **key\_path** | *in* | *s* |  |
| **key\_group** | *in* | *s* |  |
| **key\_name** | *in* | *s* |  |
| **user\_signalcb\_fun** | *in* | *u* |  |
| **user\_fun** | *in* | *u* |  |
| **key\_actions** | *in* | *u* |  |
| **user\_fun\_out** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### Reset\_Settings\_BLM\_Settings\_pChar



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **key\_path** | *in* | *s* |  |
| **key\_group** | *in* | *s* |  |
| **key\_name** | *in* | *s* |  |
| **user\_fun** | *in* | *u* |  |
| **key\_actions** | *in* | *u* |  |
| **user\_fun\_out** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### Reset\_SettingsGroup



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **key\_group** | *in* | *n* |  |
| **user\_fun** | *in* | *u* |  |
| **user\_fun\_out** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### Settings\_RPC



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **settings\_cmd** | *in* | *u* |  |
| **user\_fun** | *in* | *u* |  |
| **user\_fun\_out** | *out* | *u* |  |
| **status** | *out* | *u* |  |



## Signals

### OnChangeSignal\_Settings\_U8



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **val** | ** | *y* |  |
| **user\_fun\_out** | ** | *u* |  |
| **status** | ** | *u* |  |


### OnChangeSignal\_Settings\_S16



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **val** | ** | *n* |  |
| **user\_fun\_out** | ** | *u* |  |
| **status** | ** | *u* |  |


### OnChangeSignal\_Settings\_U32



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **val** | ** | *u* |  |
| **user\_fun\_out** | ** | *u* |  |
| **status** | ** | *u* |  |


### OnChangeSignal\_Settings\_BLM\_Settings\_pChar



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **val** | ** | *s* |  |
| **user\_fun\_out** | ** | *u* |  |
| **status** | ** | *u* |  |

