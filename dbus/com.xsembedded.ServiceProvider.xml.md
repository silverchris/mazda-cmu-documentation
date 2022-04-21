
# Dbus interface API

**com.xsembedded.ServiceProvider**


## Methods

### Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **methodName** | *in* | *s* |  |
| **arguments** | *in* | *s* |  |
| **result** | *out* | *s* |  |


### openSession



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **busName** | *in* | *s* |  |
| **objectPath** | *in* | *s* |  |
| **destination** | *in* | *s* |  |
| **sessionId** | *out* | *i* |  |
| **result** | *out* | *(iss)* |  |


### closeSession



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *i* |  |
| **result** | *out* | *(iss)* |  |


### registerAudioStream



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *i* |  |
| **streamName** | *in* | *s* |  |
| **streamModeName** | *in* | *s* |  |
| **streamType** | *in* | *s* |  |
| **focusType** | *in* | *i* |  |
| **result** | *out* | *(iss)* |  |


### requestAudioFocus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *i* |  |
| **requestType** | *in* | *i* |  |
| **result** | *out* | *(iss)* |  |


### abandonAudioFocus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *i* |  |
| **reason** | *in* | *s* |  |
| **result** | *out* | *(iss)* |  |


### audioActive



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *i* |  |
| **playing** | *in* | *i* |  |
| **result** | *out* | *(iss)* |  |


### setMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *i* |  |
| **newMode** | *in* | *s* |  |
| **destination** | *in* | *s* |  |
| **result** | *out* | *(iss)* |  |


### getMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *i* |  |
| **currentMode** | *out* | *s* |  |
| **destination** | *in* | *s* |  |
| **result** | *out* | *(iss)* |  |


### getModeList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **sessionId** | *in* | *i* |  |
| **modeList** | *out* | *(asi)* |  |
| **destination** | *in* | *s* |  |
| **result** | *out* | *(iss)* |  |


### enableStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *out* | *i* |  |
| **result** | *out* | *(iss)* |  |


### enable



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setAudioStatus** | *in* | *i* |  |
| **result** | *out* | *(iss)* |  |



## Signals

### Notify



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **signalName** | ** | *s* |  |
| **payload** | ** | *s* |  |

